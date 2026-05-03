# Hotel Booking Dataset — Data Dictionary

---

## 1. Uncleaned Dataset: `hotel_bookings.csv`

| Column Name | Data Type | Description | Null Count |
|------------|----------|-------------|-----------|
| hotel | object | Type of hotel (Resort or City) | 0 |
| is_canceled | int64 | Booking canceled (1) or not (0) | 0 |
| lead_time | int64 | Days between booking and arrival | 0 |
| arrival_date_year | int64 | Year of arrival | 0 |
| arrival_date_month | object | Month of arrival | 0 |
| arrival_date_week_number | int64 | Week number of arrival | 0 |
| arrival_date_day_of_month | int64 | Day of month | 0 |
| stays_in_weekend_nights | int64 | Weekend nights stayed | 0 |
| stays_in_week_nights | int64 | Week nights stayed | 0 |
| adults | int64 | Number of adults | 0 |
| children | float64 | Number of children | 4 |
| babies | int64 | Number of babies | 0 |
| meal | object | Meal type (BB, HB, FB) | 0 |
| country | object | Country code | 488 |
| market_segment | object | Market segment | 0 |
| distribution_channel | object | Booking channel | 0 |
| is_repeated_guest | int64 | Repeat guest (1/0) | 0 |
| previous_cancellations | int64 | Previous cancellations | 0 |
| previous_bookings_not_canceled | int64 | Previous successful bookings | 0 |
| reserved_room_type | object | Reserved room type | 0 |
| assigned_room_type | object | Assigned room type | 0 |
| booking_changes | int64 | Number of changes | 0 |
| deposit_type | object | Deposit type | 0 |
| agent | float64 | Travel agent ID | 16,340 |
| company | float64 | Company ID | 112,593 |
| days_in_waiting_list | int64 | Days in waiting list | 0 |
| customer_type | object | Customer type | 0 |
| adr | float64 | Average daily rate | 0 |
| required_car_parking_spaces | int64 | Parking spaces required | 0 |
| total_of_special_requests | int64 | Special requests count | 0 |
| reservation_status | object | Final booking status | 0 |
| reservation_status_date | object | Status date | 0 |

---

## 2. Cleaned Dataset: `cleaned_hotel_bookings.csv`

### Key Changes

- Removed columns: `agent`, `company`
- Imputed missing values: `children`, `country`
- Added features:
  - `total_stay` = `stays_in_weekend_nights + stays_in_week_nights`
  - `revenue` = `total_stay * adr`

### Engineered Columns

| Column Name | Data Type | Description |
|------------|----------|-------------|
| total_stay | int64 | Total nights stayed |
| revenue | float64 | Estimated revenue per booking |

---

## 3. Dataset Comparison

| Metric | Uncleaned Dataset | Cleaned Dataset |
|--------|------------------|----------------|
| Total Columns | 32 | 32 |
| Missing Values | Present | None |
| Derived Features | None | total_stay, revenue |
| Sparse Columns | agent, company | Removed |

---
