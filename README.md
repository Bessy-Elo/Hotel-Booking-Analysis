##  Hotel Booking Analysis 

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

This project uses Excel to explore these kinds of questions based on hotel booking data originally sourced from [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand). The goal is to uncover valuable insights from booking and cancellation patterns to assist hospitality businesses in better decision-making and operational efficiency.

---

##  Project Objectives

- Analyze booking and cancellation behavior across different guest types and hotel categories.
- Identify seasonal trends in hotel cancellations and occupancy.
- Evaluate how room assignment affects cancellations.
- Determine which countries contribute most to cancellations.
- Generate insights to help hoteliers plan pricing, staffing, and room allocation strategies.

---

##  Key Business Questions & Solutions

### 1. **Which guest types are most likely to cancel bookings?**

| Guest Type  | Total Guests | Cancelled Bookings |
|-------------|--------------|---------------------|
| Adult       | 2,070        | 6,144               |
| Family      | 3,175        | 9,109               |
| Single      | 6,555        | 22,577              |
| Two-Adult   | 32,424       | 81,560              |

** Insight:**  
Two-adult and single guest types lead to the highest number of cancellations. Marketing and reservation strategies can be tailored accordingly.

---

### 2. **Do mismatched room assignments influence cancellations?**

| Room Status | Total Guests | Cancelled Bookings |
|-------------|--------------|---------------------|
| Matched     | 43,422       | 104,473             |
| Unmatched   | 802          | 14,917              |

** Insight:**  
Even though unmatched rooms are fewer, they result in significantly higher cancellation rates relative to their volume. Room assignment accuracy should be prioritized.

---

### 3. **When is the peak cancellation season?**

| Month      | Total Guests | Cancelled Bookings |
|------------|--------------|---------------------|
| January    | 1,807        | 5,929               |
| February   | 2,696        | 8,068               |
| March      | 3,149        | 9,794               |
| April      | 4,524        | 11,089              |
| May        | 4,677        | 11,791              |
| June       | 4,535        | 10,939              |
| **July**       | **4,742**        | **12,661**              |
| **August**     | **5,239**        | **13,877**              |
| September  | 4,116        | 10,508              |
| October    | 4,246        | 11,160              |
| November   | 2,122        | 6,794               |
| December   | 2,371        | 6,780               |

** Insight:**  
Cancellations peak in **July and August**, likely due to summer travel plans. Hotels should prepare for higher cancellations during this time with flexible policies or overbooking strategies.

---

### 4. **Which hotel type has more bookings and cancellations?**

#### Bookings by Hotel Category

| Hotel Type   | Total Bookings |
|--------------|----------------|
| City Hotel   | 79,330         |
| Resort Hotel | 40,060         |
| **Total**    | **119,390**    |

#### Cancellations by Hotel Category

| Hotel Type   | Total Cancellations |
|--------------|----------------------|
| City Hotel   | 33,102               |
| Resort Hotel | 11,122               |
| **Total**    | **44,224**           |

** Insight:**  
City Hotels not only receive more bookings but also face significantly higher cancellations. This could be influenced by shorter stays or business travelers' changing plans.

---

### 5. **Which countries contribute the most to guest cancellations?**

| Country | Total Bookings | Cancelled Bookings |
|---------|----------------|---------------------|
| FRA     | 10,415         | 1,934               |
| GBR     | 12,129         | 2,453               |
| PRT     | 48,590         | 27,519              |

** Insight:**  
Portugal (PRT) has the highest cancellation volume, followed by the UK (GBR) and France (FRA). These countries might require different communication or booking confirmation strategies.

---

##  Excel Features & Techniques Used

- **Pivot Tables**: Summarized bookings and cancellations across categories
- **COUNTIFS**: Conditional count formulas to break down metrics
- **Slicers**: Enabled year-based filtering (2015, 2016, 2017)
- **Conditional Formatting**: Highlighted peak months and categories
- **Filtering & Sorting**: Used to rank months, countries, and guest ty
## Room_Status 
=
