<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Project+Overview;+PD+LGD+EAD+Model&center=true&size=30&font=Lato&color=blue&speed=20">
  </a>
</h1>

# 📂 **Loan-Risk-PD-LGD-AND-EAD-Model**

## 📚 *Introduction*
This project focuses on developing a credit scoring model to assess lending risks. It involves predicting the Probability of Default (PD), Loss Given Default (LGD), Exposure at Default (EAD), and Expected Loss (EL) using logistic and linear regression. These metrics help estimate potential losses and determine capital requirements for the bank. The project uses feature selection, data preprocessing, and dummy variable creation to build a model that calculates individual credit scores and portfolio-wide risk.

## ⚙️ *Methodology*
**Logistic Regression**:
<br>
Use logistic regression to predict the probability of default and Loss Given Default (LGD), as default and recovery rate are binary outcomes (1 for default with loss, 0 for no default and no loss). Set a threshold based on the predicted probability: clients with probabilities above the threshold are predicted to default/have a loss, while those below are predicted to not default/have no loss. Evaluate the model using the ROC curve and confusion matrix.

**Linear Regression**:
<br>
Use linear regression to capture the factors influencing loss size and predict Exposure at Default (EAD). The model provides a clear prediction of EAD based on the relationship between features and the outcome. Evaluate model performance using the correlation matrix.

## 📝 *Summary* 
This project builds a credit risk model by estimating PD, LGD, EAD, and EL. Logistic regression predicts the Probability of Default, while linear regression estimates recovery rates. The Expected Loss is calculated for both individual borrowers and the overall portfolio. The model is designed to help banks assess potential losses and determine capital reserves. By focusing on both individual and portfolio risk, it offers valuable insights for effective credit risk management.
