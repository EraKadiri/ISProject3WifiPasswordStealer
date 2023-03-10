# ISProject3WifiPasswordStealer

This project is an Application Programming Interface that aims to obtain the passwords of Wi-Fi's that a particular PC has once logged in. It was developed using C# using .NET framework.
The Wi-Fi Password Stealing is a program that has these features:
  - Provides an endpoint that outputs the list of the names and passwords of all Wi-Fi's the particular device has logged in beforehand.
  - Sends the list of Wi-Fi's automatically to the email account, where all the passwords are technically stolen.

### Prerequisites

C# and .NET framework need to be installed and the libraries added in the code need to be imported before executing the program.

## Executing the program

After intalling the project you need to execute the project in order to use the endpoint mentioned above.

## Built With

* [C#](https://docs.microsoft.com/en-us/dotnet/csharp/) - The programming language used
* [.NET Framework](https://docs.microsoft.com/en-us/dotnet/framework/) - The framework used

## What you need to know

You need to add the email username in the variables shown below:

![image](https://user-images.githubusercontent.com/73954017/211196437-255e25e9-71f3-481e-945b-57157012fe08.png)

The email of the sender should have the two-step authentification turned on and it should have a generated app password to succesfully run the code:

![image](https://user-images.githubusercontent.com/73954017/211196185-2fc929dc-c487-44aa-bbeb-9dc2144ce9ee.png)


## Authors

* Era Kadiri - EraKadiri(https://github.com/erakadiri)
* Erjon Kosumi - ErjonKosumi(https://github.com/erjonkosumi)
* Erona Syla - EronaSyla(https://github.com/ronlyss)

## Important

Since the email username of the receiver is needed in the code, you need to be cautious that any execution of the code will automatically send the list of your PC's Wi-Fi's and passwords to the receiver, so you need to add your personal email. Also, it is necessary to note that this project has educational and informational means only, and it is not recommended for malicious use. Password stealing is a serious problem because it can have serious consequences for the individuals and organizations whose passwords are stolen and it can lead to further cyber attacks. Therefore, it is important to protect your passwords and detect any prevention of Wi-Fi password stealing
