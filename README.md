# ATM
    The ATM / Online Banking Project
    This project is about ATM via Python. Before the starting this project, fisrt step is to plan the steps.For it, I used Case Diagram and Class Diagram techniques of UML. UML is called as Unified Modeling Language. It is consist of an set of diagram, developed to help system and software developers for specifying and etc.In case diagram, there are four(4) different elements which are system, actor, use case and relationship. System is whatever er are developing or writing. So, ATM is system in case diagram and it is shown as rectangle. An actors are represented by human figures. They could be a person, an organization, or other systems and etc. 
    In that diagram, the users and bank  are represented by it. Then, use case is depicted with oval shape and it represents an action that accomplishes some sort of task 
within the system. Use cases are *"Log in", "Check Balance", "Insert Money", "Withdraw Money", "Transfer Money", "Edit Information", and "Others"*. They are benefits of ATM. 
All of use cases are in rectangle since they occurs within ATM.
		Relationship is last element. There are three(3) types of it that are include, extend and generalization. When user insert the debit card to ATM, Log in case verify the password. If the user enter wrong password, display error will be indicated.  Then, there is a relationship among *"Withdraw Money and Transfer Money"* and *"Veirfy sufficient balance and Insufficient Balance"*. When the user want to transfer a money or withdraw a money, ATM will be contact with Bank. If there are enough money to do them, this process will be achieved, or not, incoming with Insufficient Balance. On the other hand, there is an also relationship *"Edit information","Change information" and "delete account"*. Then they are also will contact with Bank for synchronisation.
    The class diagram is the main building block of object-oriented modeling. It is used for general conceptual modeling of the structure of the application, and for detailed modeling translating the models into programming code. 
    There will be two main classes which are User and ATM. Check Balance, InsertMoney, WithdrawMoney, TransferMoney, EditInformation and OtherOperations are inherited from ATM class. Current and Saving accounts are inherited from CheckBalance and TransferToNumber and TransferToAccount are inherited from the TransferMoney.
In light of the information, the python code should include: 
*Error controls (try/except)
*Holding information in a txt, csv or json file
* GUI (PyQT5)
