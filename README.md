# Mobile_price_prediction_using_Naive_bayes
**Overview:-**
This project aims to predict the price range of mobile phones based on their specifications using the Naive Bayes algorithm. The dataset contains various features of mobile phones, and the target variable is the price range. The Naive Bayes classifier is used because it is a simple yet effective probabilistic classifier that works well with categorical data.

**Dataset:-**
The dataset mobile_data.csv contains the following features:

battery_power: Total energy a battery can store in one time measured in mAh

blue: Whether the phone has Bluetooth (1 = yes, 0 = no)

clock_speed: Speed at which microprocessor executes instructions

dual_sim: Whether the phone supports dual SIM (1 = yes, 0 = no)

fc: Front camera megapixels

four_g: Whether the phone has 4G capability (1 = yes, 0 = no)

int_memory: Internal memory in GB

m_dep: Mobile depth in cm

mobile_wt: Weight of mobile phone

n_cores: Number of cores in the processor

pc: Primary camera megapixels

px_height: Pixel resolution height

px_width: Pixel resolution width

ram: Random Access Memory in MB

sc_h: Screen height of mobile in cm

sc_w: Screen width of mobile in cm

talk_time: Longest time that a single battery charge will last when you are talking

three_g: Whether the phone has 3G capability (1 = yes, 0 = no)

touch_screen: Whether the phone has a touch screen (1 = yes, 0 = no)

wifi: Whether the phone has wifi (1 = yes, 0 = no)

price_range: Target variable with 4 values (0: low cost, 1: medium cost, 2: high cost, 3: very high cost)

**Key Findings:**
**Data Preprocessing:**
The dataset required minimal preprocessing as it was clean and well-structured. Feature selection and scaling were essential steps to ensure that the model could effectively learn from the data.

**Model Training:**
The Naive Bayes classifier, known for its efficiency and ease of implementation, was chosen for this task. Despite the independence assumption of Naive Bayes, the classifier performed reasonably well on this multi-class classification problem.

**Model Performance:**
The Naive Bayes model achieved satisfactory accuracy, indicating its capability to differentiate between different price ranges based on the given features. The confusion matrix and classification report revealed that while the model performed well overall, there were some misclassifications, especially between adjacent price categories.

**Conclusion:-**
The Naive Bayes classifier proved to be an effective and efficient choice for predicting mobile phone price ranges based on hardware specifications. While it has its limitations, its strengths in simplicity, interpretability, and performance make it a valuable tool for this type of classification problem. By addressing its limitations and exploring more advanced techniques, we can further enhance the accuracy and applicability of the model, making it a powerful asset for mobile phone price prediction.
