I have been writing code for physics based calculations in commercial software products for 3 decades: fluid flow, heat transfer, chemical reactions, reservoir simulation.

I started in the dark ages with FORTRAN and a card punch. The first 2 years of my PhD work I did with a line editor. Since then, I've learned C, C++, and object oriented design, along with bits of JAVA and C#. Plus, of course, a plethora of IDE's and version control tools.

- 🔭 I recently completed the Springboard Machine Learning Engineering Certification Program.
- ⚡ Fun fact: I'm a huge fan of performing arts. Mainly classical music (chamber, symphonic, baroque), but also theater, dance, and opera.

## Capstone Project for MLE Certification Program
It is a multi-class classification task in environmental science. I used `pycaret` to quickly set-up and run a large number of models. I did have to write all the plotting code myself (`pandas`, `matplotlib`, `seaborn`). Here are some results:
- x-axis: encoding technique for non-ordinal, high cardinality categorical feature; minority classes over-sampling technique (factor=3 or 1.5)
- y-axis: metric value
- colored dots: model
### overall accuracy
![model_accuracy](https://github.com/LoriNewhouse/Springboard_Machine_Learning_Engineering_bootcamp/blob/main/capstone_project/images/model_accuracy.PNG)

### model tuning
Decision Tree and CatBoost models were tuned using 3-fold cross-validation with 15 iterations.
![tune_by_class](https://github.com/LoriNewhouse/Springboard_Machine_Learning_Engineering_bootcamp/blob/main/capstone_project/images/tune_by_class.PNG)

### finalized model
Decision Tree model was finalized by fitting with all the data and the tuned hyper-parameters.
![finalized_by_class](https://github.com/LoriNewhouse/Springboard_Machine_Learning_Engineering_bootcamp/blob/main/capstone_project/images/finalized_by_class.PNG)

Go here for more information
https://github.com/LoriNewhouse/Springboard_Machine_Learning_Engineering_Certification_Program/blob/main/capstone_project/README.md


<!--
**LoriNewhouse/LoriNewhouse** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
