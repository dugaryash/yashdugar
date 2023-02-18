<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yash Dugar</title>
  <style>
    /* Style for the navigation bar */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #333;
      color: white;
      padding: 20px;
    }
    nav ul {
      list-style: none;
      display: flex;
      margin: 0;
      padding: 0;
    }
    nav li {
      margin-right: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-size: 20px;
    }
  </style>
</head>
<body>
  <nav>
    <h1>My Personal Website</h1>
    <ul>
      <li><a href="#about-me">About Me</a></li>
      <li><a href="#my-projects">My Projects</a></li>
      <li><a href="#contact-me">Contact Me</a></li>
    </ul>
  </nav>
  
  <main>
    <section id="about-me">
      <h2>About Me</h2>
      <p>Insert your personal introduction here.</p>
    </section>
    
    <section id="my-projects">
      <h2>My Projects</h2>
      <ul>
        <li><a href="https://www.stat.cmu.edu/capstoneresearch/600files/poster1.pdf"> Procedural Evaluation-based Hospital Rating Prediction: A Data-driven Approach </a></li>
        <h3> <h2> Summary </h2> In our study, we developed a predictive model for hospital ratings using various predictor variables, such as the facility type, rating, and the cost, value, and quality of procedures. We evaluated five classification models and found that Random Forest and XGBoost produced similar results, with XGBoost having slightly lower MCR but similar AUC. Our analysis identified Rating.Safety, Rating.Readmission, and Rating.Experience as the most important features in determining hospital ratings, respectively. These findings align with the notion that the safety of a hospital is a primary concern when comparing hospitals, and hence, it is a crucial factor in our classification model. Interestingly, our results showed that the cost of procedures was comparable between low- and high-rated hospitals, with only hip/knee replacement procedures showing a cost difference of approximately 1.5%. </h3>
        
        <li><a href="#">Developing a Loan Classification Model to Predict Repayment Ability: A Comparison of Machine Learning Models</a></li>
        <h3> <h2> Summary </h2> The purpose of our study was to develop a loan classification model that can efficiently predict the repayment ability of loan applicants, in order to prevent financial loss for the bank. We first cleaned the dataset and conducted exploratory data analysis and feature engineering, addressing missing values and imbalanced data sets. We proposed four machine learning models - Random Forest, Logistic Regression, Support Vector Machine, and K-Nearest Neighbors - to predict loan repayment, and used both Randomized Search Cross Validation and Grid Search Cross Validation to tune parameters in different situations. Our experiments showed that the random forest model had the highest accuracy and best fit for the dataset, while the logistic regression model with L2 penalty had the highest AUC score. As expected, we found that borrowers with higher annual income and FICO scores were more likely to repay the loan, while those with lower interest rates and smaller installments were also more likely to pay back the loan in full. </h3>
       
        <li><a href="#">Project 3</a></li>
        
      </ul>
  
   </main>
  
   <footer>
    <div>
      <p>Connect with me:</p>
      <a href="https://www.instagram.com/_yash_dugar"><img src="Instagram_logo.png" width = "30" height= "30"></a>
      <a href="https://www.linkedin.com/in/yash-dugar/"><img src="LinkedIn_logo.png" width = "30" height= "30"></a>
      <a href="https://github.com/dugaryash"><img src="Github_logo.png" width = "30" height= "30"></a>
    </div>
    <p>&copy; 2023</p>
  </footer>
</body>
</html>
