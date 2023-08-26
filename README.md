# Decision-Tree
**Project Title :** Prediction of iris.csv dataset for decision tree algorithm using supervised learning machine algorithm 

**Problem Statment :** A american based botanical garden a grow iris flower in there labs but using bio technology in a single tree differnet types of variety flowers is grow.find out as a data cientist how much accuracy is there all categories contains same species.
# Load the Iris dataset
iris = load_iris()
X = iris.data
y = iris.target

# Split the dataset into training and testing sets
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Create a Decision Tree classifier
decision_tree = DecisionTreeClassifier()

Project Apporach :
![image](https://github.com/Pankajpanday29/Decision-Tree/assets/128885642/6edb1ea5-78cb-435d-b1d6-31a606be23fe)


# Make predictions on the test data
y_pred = decision_tree.predict(X_test)

Project Accuracy :
![image](https://github.com/Pankajpanday29/Decision-Tree/assets/128885642/f81857b5-51aa-46d8-b6c8-7732dd990a81)


