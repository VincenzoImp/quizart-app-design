# QuizArt App Design

## **Introduction**

**QuizArt** is an interactive mobile application designed to engage users with cultural heritage while offering incentives through gamified quizzes. The app allows users to explore cultural sites, participate in educational quizzes, earn points, and redeem those points for vouchers that can be used to visit various cultural sites. The core idea is to merge education and entertainment, promoting learning while encouraging visits to cultural landmarks.

## **Key Features**

### 1. **Daily and Weekly Quizzes**
   - **Daily Quizzes**: Users can play daily quizzes with 10 multiple-choice questions. The difficulty of the questions increases progressively, and users earn more points as they advance. Each question has a time limit of 10 seconds, and curiosity facts are displayed between questions to provide extra knowledge.
   - **Weekly Quizzes**: Held live at a specific time once a week, these quizzes allow users to compete against others. Players join a waiting room and start the quiz together when the countdown reaches zero. These quizzes offer higher point rewards and a "victory bonus" for the winners.

### 2. **Cultural Heritage Information Board**
   - **Nearby Sites**: The app uses GPS functionality to provide a list of nearby cultural heritage sites, displayed in order of proximity. Users can click on each item for more detailed information, such as:
     - Description of the cultural site
     - Ticket prices
     - Average visit duration
     - Location (linked to Google Maps)
     - Website URL of the site

### 3. **Rewards Shop**
   - **Points System**: Users accumulate points by participating in the daily and weekly quizzes. These points can be converted into vouchers for cultural site tickets. The conversion rate is 10,000 points = 1 euro.
   - **Voucher Redemption**: After converting points into vouchers, users receive a QR code that can be scanned at participating sites for entry. If the voucher value exceeds the ticket price, the remaining balance can be used for future visits.
   - **Voucher Validity**: Vouchers are valid for one year from the issue date.

### 4. **User Experience & Interface**
   - The app prioritizes simplicity and user-friendliness. Key tasks such as quiz participation, site exploration, and reward redemption have been designed to be intuitive.
   - **Visual Design**: The interface includes clear navigation elements, color-coded sections, and minimalistic iconography to ensure easy usability.
   - **Testing Feedback**: Several rounds of user testing were conducted to ensure the design meets user needs and expectations.

## **Design and Development Process**

### 1. **Need Finding and Research**
   - The development began with extensive user research through interviews and surveys to identify user needs and preferences. The goal was to understand what users would find engaging and educational in an app about cultural heritage.
   - We also analyzed similar applications and existing services to identify successful elements to incorporate into **QuizArt**.

### 2. **Storyboarding and Task Definition**
   - We created storyboards to visualize the user experience and define key tasks the app should facilitate. These included quiz participation, exploring nearby cultural sites, and redeeming points for vouchers.
   - The tasks were designed to align with the app's goal of promoting learning while providing an enjoyable, game-like experience.

### 3. **Prototyping**
   - **Low-Fidelity Prototyping**: The initial prototypes were paper-based, focusing on the structure and user flow. These were used for early-stage feedback and iteration.
   - **Digital Prototypes**: After refining the paper prototypes, we moved to **Marvel** for digital prototyping. This allowed for interactive testing and further iterations based on feedback.
   - Multiple versions of the prototype were created, and user feedback was continuously incorporated to improve the design. The final version was tested thoroughly and refined for clarity, ease of use, and visual appeal.

### 4. **Usability Testing**
   - **Testing Methods**: We conducted usability testing using the "Think Aloud" method, where participants were asked to voice their thoughts as they interacted with the app. This helped us identify potential usability issues and gain insights into user preferences.
   - **Test Results**: The testing process provided valuable feedback that informed the final design adjustments, including improvements in navigation and usability.

## **Feasibility Study**

The most ambitious feature of **QuizArt** is the voucher redemption system. A study was conducted to evaluate the feasibility of implementing such a feature, similar to the **18app** system used in Italy.

### Key Findings:
- **Technical Feasibility**: The system for converting points into vouchers and integrating QR codes is technically feasible. Users can generate and redeem vouchers easily through the app.
- **Partnerships with Cultural Sites**: One major challenge is that not all cultural heritage sites may be willing to accept vouchers from an unfamiliar app. We propose forming partnerships with these sites and offering them visibility within the app in exchange for their participation.
- **Public Sector Support**: The success of the app could be further supported by seeking involvement from public organizations or governmental bodies to promote **QuizArt** as a trusted platform for cultural education and tourism.

### Similar Services:
- **MilanoGuida** offers a similar voucher system, allowing users to purchase vouchers for over 500 cultural sites in Lombardy, which serves as a justification for the feasibility of implementing a similar feature in **QuizArt**.

### Sponsorship Model:
- **Visibility for Cultural Sites**: Cultural sites can request to be featured more prominently in the app’s "Information Board" for increased visibility. Additionally, they can create custom quiz questions based on their history or art to engage users more deeply.
  
## **Point System and Rewards**

We designed a point system that ensures balance between user effort and rewards. Here’s a breakdown of the point allocation for quizzes:

- **Daily Quizzes**: A maximum of 275 points can be earned per day by answering all questions correctly.
- **Weekly Quizzes**: Players can earn up to 15,400 points, including the victory bonus, by winning the weekly quiz.
- **Point Conversion**: 10,000 points equal 1 euro. The points increase incrementally based on the quiz’s difficulty level, with more challenging questions earning higher rewards.
  
### Example Scenarios:
- **Max Points from Daily Quiz**: 275 points (for 10 correct answers).
- **Max Points from Weekly Quiz**: 15,400 points (for 10 correct answers + victory bonus).
- **Weekly Points Average**: A player could earn approximately 9,625 points by correctly answering all questions in half of the daily quizzes in a week.

## **Conclusion**

The **QuizArt** app successfully integrates education, entertainment, and rewards in a user-friendly interface. Through a structured design process, we were able to create an engaging app that promotes learning about cultural heritage while offering tangible rewards. By conducting thorough testing, including usability studies and a feasibility analysis of the voucher system, we have ensured that **QuizArt** is both viable and enjoyable.

The project was a valuable learning experience, helping us understand the complex challenges involved in developing an app that meets both user needs and business goals. Future improvements could include expanding quiz categories, integrating user preferences, and scaling the app's reach with additional partnerships.

## **Next Steps**
- **Partnership Expansion**: Secure agreements with more cultural sites for voucher redemption.
- **Feature Enhancements**: Expand quiz categories and introduce personalized content.
- **Mobile App Optimization**: Optimize performance for a broader range of devices and improve GPS functionality.
