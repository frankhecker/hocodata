# hocodata datasets

This directory contains the following Howard County datasets:

* `hocomd-2014-precinct-council.csv`. This dataset maps the 118 Howard
  County election precincts to the county council districts in which
  those precincts are included. The data is taken from the
  per-precinct [2014 general election results][] (PDF) from the
  [Howard County Board of Elections][]. The dataset has two variables
  with meanings and types as follows:
  - `Precinct`. The precinct designator in the form '000-000' (e.g.,
     '006-035'). (character string)
  - `Council.District`. The county council district (1 through 5) in
     which the precinct is included. (character string)
* `hocomd-2014-general-election-turnout.csv`. This data contains
turnout statistics for each of the 118 Howard County precincts in the
2014 general election. The data is taken from the per-precinct [2014
general election results][] (PDF) from the [Howard County Board of
Elections][]. The dataset has five variables:
  - `Precinct`. The precinct designator in the form '000-000' (e.g.,
    '006-035'). (character string)
  - `Polling.Place`. The polling place for the precinct. (Note that
    one polling place may server multiple precincts.) (character
    string)
  - `Reg.Voters`. The number of registered voters (of all parties) in
    the precinct as of election day. (integer)
  - `Cards.Cast`. The number of people casting ballots in the precinct
    on election day. (integer)
  - `Pct.Turnout`. The number of people casting ballots in the
    precinct on election day as a percentage of registered voters in
    that precinct. (numeric)

[2014 general election results]: http://www.howardcountymd.gov/WorkArea/linkit.aspx?LinkIdentifier=id&ItemID=6442477038&libID=6442477030
[Howard County Board of Elections]: http://www.howardcountymd.gov/Departments.aspx?id=4294968268

