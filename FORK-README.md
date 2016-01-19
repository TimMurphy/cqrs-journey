# CQRS Journey - FORK

The sole purpose of this fork is have the solution compile and run on my machine. See commit messages for more details. Use branch `fork/master`.

## Prerequisites

This fork "Work on My Machine" with these prerequisites:

- Windows 10
- Microsoft Visual Studio 2015
- Microsoft Azure Tools - v2.8 (Its probably this comes with Microsoft Visual Studio 2015)
- [Microsoft SQL Server 2014 Express](https://www.microsoft.com/en-us/download/details.aspx?id=42299) 

## Building CQRS Journey

- Run `.\scripts\Install-Database.ps1`
- Copy `.\source\Infrastructure\Azure\Settings.Template.xml` to `.\source\Infrastructure\Azure\Settings.xml`. `Settings.xml` can be edited later. 
- Run `.\Install-Packages.ps1`
- Open `.\source\Conference.sln` and Build Solution

## Run CQRS Journey

I'm reading `CQRS Journey` not running it. See https://github.com/mspnp/cqrs-journey/blob/master/docs/Appendix1_Running.markdown#scenario-4-compute-emulator-windows-azure-service-bus-table-storage-event-store for run instructions.