# Uncovering the Drivers of Hotel Cancellations: An EDA Project
**August 2023**

![Hotel Lobby](https://images.unsplash.com/photo-1566073771259-6a8506099945?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80)
*Photo by [Mohd Aram on Unsplash](https://unsplash.com/@aram_mohd)*

---

## 📋 Project Overview

This project performs an in-depth exploratory data analysis (EDA) on a hotel booking demand dataset. The primary objective is to identify the key factors that influence booking cancellations and to uncover other significant patterns in customer behavior.

Hotels lose a significant amount of revenue due to cancellations. By understanding *why* and *when* customers cancel, the business can develop data-driven strategies to mitigate these losses, optimize pricing, and improve guest retention.

---

## 💾 Dataset

* **Source:** [Kaggle - Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
* **Description:** The dataset contains booking information for a city hotel and a resort hotel, collected between July 2015 and August 2017. It includes details such as lead time, length of stay, guest demographics, special requests, and cancellation status.

---

## 📊 Key Questions Explored

This analysis seeks to answer a comprehensive set of questions to build a holistic view of the hotel's operations:

#### Cancellations & Bookings:
* What is the overall cancellation rate?
* Which hotel type (City vs. Resort) experiences more cancellations?
* How does lead time affect the likelihood of cancellation?

#### Customer Behavior & Segmentation:
* What are the busiest months for bookings?
* Where do most guests come from?
* How does loyalty (repeat guests) impact cancellation rates?
* Which market segments are the most valuable and which are the riskiest?
* Are guests who make special requests more committed to their booking?

#### Revenue & Pricing:
* How does the Average Daily Rate (ADR) fluctuate throughout the year?

---

## 💡 Key Insights & Actionable Recommendations

### Findings
1.  **High Cancellation Rate:** A significant **37%** of all bookings were canceled.
2.  **City Hotels are Riskier:** City hotels suffer from a substantially higher cancellation rate (~42%) compared to Resort hotels (~28%).
3.  **Lead Time is a Critical Factor:** The longer a booking is made in advance, the higher the probability of cancellation.
4.  **Loyalty Pays Off:** Repeat guests have a dramatically lower cancellation rate (**~15%**) compared to new guests (**~37%**).
5.  **Guest Engagement Matters:** Guests who make special requests are far less likely to cancel.

### Recommendations
* **Implement Dynamic Deposit Policies:** Require non-refundable deposits for bookings with long lead times or from high-risk market segments like "Groups".
* **Develop a Robust Loyalty Program:** Invest in loyalty programs to encourage repeat business, as these guests are far more reliable.
* **Encourage Guest Engagement:** Actively prompt for special requests during the booking process to increase guest investment in their stay.

---

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **Pandas:** For data manipulation and cleaning.
* **Matplotlib & Seaborn:** For data visualization.
* **PyWaffle:** For creating waffle charts.
* **Google Colab / Jupyter Notebook:** As the development environment.

---

## 🚀 How to Run this Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Install required libraries:**
    ```bash
    pip install pandas matplotlib seaborn pywaffle
    ```
4.  **Open the notebook:**
    Open the `.ipynb` file in Jupyter Notebook or Google Colab.
5.  **Run the cells:**
    Execute the cells sequentially to see the analysis.

---

## 🔮 Future Work

The next logical step for this project would be to move from descriptive analytics (EDA) to predictive analytics. A machine learning model (e.g., Logistic Regression, Random Forest) could be trained on this data to **predict whether a new booking is likely to be canceled**. This would allow the hotel to take proactive steps to prevent potential cancellations.
