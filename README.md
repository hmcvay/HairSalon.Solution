# Eau Claire's Salon

#### By Hayley McVay

<img src="readMeImage.png" width="auto">

## Description

Web App for Eau Claire's Salon to keep track of their business's stylists and the stylists's clients. This project creates and implements a backend database to allow a user add/edit/view/delete entries on the frontend.

<br>

## Technologies Used

* C#
* .NET 5.0
* Microsoft EntityFrameworkCore
* ASP.NET MVC
* MySQL Workbench

<br>

## Setup/Installation Requirements

* Install [.NET5 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-5.0.401-macos-x64-installer), if you do not already have it installed
* In order to use this application, you will need [MySQL Workbench](https://dev.mysql.com/downloads/workbench/) installed
* Cone this repository
* In MySQL Workbench, click the Administration tab, then click, Data Import/Restore
* Next select "Import from self-contained file," and using the file browser locate the file "hayley_mcvay.sql" in this project's root directory
* Next click New in the Default Schema to be Imported To, and name your schema "hair_salon"
* Next, Start Import.
* Now, navigate to the "HairSalon" directory of this project and create `appsettings.json` file
* Input the following code to the file:<br>
`{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=hair_salon;uid=root;pwd={YOURPASSWORDHERE};"
  }
}`
* replace `{YOURPASSWORDHERE}` with the password you used when setting up MySQLWorkbench
* While still in the HairSalon directory, run `dotnet restore` to restore all dependencies
* Run `dotnet build`
* Run `dotnet run` to run the program.
* You can now copy and paste the localhost link to your browser to view application

<br>

## Known Bugs

* No known issues

<br>

## License

[ISC](https://opensource.org/licenses/ISC)

<br>

## Contact

_Copyright (c) 2022 Hayley McVay_

