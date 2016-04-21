![ProgrammingTheWorld](https://github.com/Beninho85/ProgrammingTheWorld/Resources/Images/ptw-cover.png)

## Synopsis

Programming The World is an Open Source Project aspiring to program everything we know.<br />
The goal is to give access of information for free to every people in this world.<br />
The first version will be programmed in Swift

## What is the problem

Nowadays, few companies contains the major part of information. <br />
In the other side, the web is a real mess.<br />
ProgrammingTheWorld wants to become the ultimate free public access to information.<br />
The time has come to collaborate together for designing a better Web.

## The Goal

Providing access to datas for everybody everywhere:<br />
    - Web Access<br />
    - Mobile Applications<br />
    - Consoles<br />
    - Library for programmers<br />
    - API's<br />
    - Other?<br />

## What kind of data?

EVERYTHING OF EVERY TYPE! From wikipedia-like information (Animals, Peoples, History) to every domains : Science, Mathematics, Music, any type of content : Articles, Videos... It's time to reapprorite our datas! Of course every lang is accepted.

## Examples

Here is some samples of what ProgrammingTheWorld could be in a console:<br /><br />

-> print all animals of kind bird limit 2

will show: 

| ID | Name   | Family       |
|----|--------|--------------|
| 1  | falcon | Falconidae   |
| 2  | owl    | Strigiformes |

<br /><br />

-> download all animals of kind bird limit 1000 order NAME desc format .xls

will create a xls file with all informations.

## Main project Architecture

- Big Central Database<br />
         =<br />
         =<br />
         =<br />
    Interacts with<br />
         =<br />
         =<br />
         =<br />
- ProgrammingTheWorld Code<br />
         =<br />
         =<br />
         =<br />
    Interacts with<br />
         =<br />
         =<br />
         =<br />
- Access providers: Web, API, Consoles, Mobile App..<br />
         =<br />
         =<br />
         =<br />
    Interacts with<br />
         =<br />
         =<br />
         =<br />
        YOU

## Architecture of ProgrammingTheWorld code

- On top : Main Superclass of datas (Meta datas : object class, theme class, tag class...)
- Everything codable
- Bottom: Savable Objects: Objects we can store in the database

## Steps for a functionnal project

- Creation of a Swift Server connected to a database
- Designing first sample database
- Creation of main superclasses ( Object, Theme... )
- Creating sample classes
- Inserting sample datas
- Creation of a simple web platform

## Contributors

Everybody can contribute. If you are a developer, you can send your commits.<br />
For non-programmers, if you think you can help, you can contact us at contactprogrammingtheworld@gmail.com<br />
For providing datas, you have to wait when data insertion will be opened.

## Why contribute?

To make the world better, for data freedom and universal access.

## License

**ProgrammingTheWorld** is available under the MIT license. See the [LICENSE](https://github.com/Beninho85/ProgrammingTheWorld/Resources/LICENSE.md) file for more info.
