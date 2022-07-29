# Eau Claire's Salon

#### A handy tool designed for Claire's Salon, allowing her to keep track of her stylists and their clients using a SQL database.

#### By Daniel Ware

## Technologies Used

* C#
* Entity
* SQL
* .NET

## Setup/Installation Requirements

* Clone repository from github
* Create an appsettings.json file in HairSalon directory and add the following:
  { "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=[Daniel_Ware];uid=root;pwd=[YOUR_PASSWORD];" } }
* Import daniel_ware.sql database into SQL Workbench
* Navigate to HairSalon directory and run dotnet restore
* Run dotnet run to and open web browser to http://localhost:5000 to view

## Known Bugs

* None

## License

MIT  (c) 2022

## Contact Information

Daniel Ware <waredanielb@gmail.com>