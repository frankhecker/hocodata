# hocodata/datasets

This directory contains the following datasets for Howard County,
Maryland:

* [`GG14_Turnout_by_party_by_precinct.csv`][]. This dataset is the CSV
  version of [`GG14_Turnout_by_party_by_precinct.xlsx`][], state-wide
  precinct-level turnout data published by the Maryland State Board of
  Elections as part of its [2014 general election reports][ge2014].
* [`hocomd-2014-precinct-council.csv`][]. This dataset maps the 118
  Howard County election precincts to the county council districts in
  which those precincts are included. The data is taken from the
  per-precinct [2014 general election results][] (PDF) from the
  [Howard County Board of Elections][]. The dataset has two variables
  with meanings and types as follows:
  - `Precinct`. The precinct designator in the form '000-000', e.g.,
     '006-035' (character string).
  - `Council.District`. The county council district ('1' through '5')
     in which the precinct is included (character string).
* [`hocomd-2014-general-election-turnout.csv`][]. This dataset
  contains turnout statistics for each of the 118 Howard County
  precincts in the 2014 general election. The data is taken from the
  per-precinct [2014 general election results][] (PDF) from the
  [Howard County Board of Elections][]. The dataset has five
  variables, with meanings and types as follows:
  - `Precinct`. The precinct designator in the form '000-000', e.g.,
    '006-035' (character string).
  - `Polling.Place`. The polling place for the precinct, which may
     serve multiple precincts (character string).
  - `Reg.Voters`. The number of registered voters (of all parties) in
    the precinct as of election day (integer).
  - `Cards.Cast`. The number of people casting ballots in the precinct
    on election day (integer).
  - `Pct.Turnout`. The number of people casting ballots in the
    precinct on election day as a percentage of registered voters in
    that precinct (numeric).
* [`Voting_Precincts_Cartogram.zip`][]. This dataset contains a map of
  Howard County precincts sized according to the number of registered
  voters in the precinct at the time of the 2014 general election
  (ESRI shapefile). For more information see the documents “Creating
  Howard County Precinct Cartograms Based on 2014 Registered Voters”,
  [Part 1][cg1] and [Part 2][cg2].
* [`Council_Districts_Cartogram.zip`][]. This dataset contains a map
  of Howard County Council districts matching the precinct-level
  cartogram (ESRI shapefile).
* [`Legislative_Districts_Cartogram.zip`][]. This dataset contains a
  map of Maryland state legislative districts matching the
  precinct-level cartogram (ESRI shapefile).
* [`Congressional_Districts_Cartogram.zip`][]. This dataset contains a
  map of US Congressional districts matching the precinct-level
  cartogram (ESRI shapefile).
* [`Voting_Precincts_Deformation_Grid.zip`][]. This dataset contains
  the defomration grid by which the precinct and district cartograms
  above were created (ESRI shapefile).

[`GG14_Turnout_by_party_by_precinct.csv`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/GG14_Turnout_by_party_by_precinct.csv
[`GG14_Turnout_by_party_by_precinct.xlsx`]: http://www.elections.state.md.us/elections/2014/turnout/general/GG14_Turnout_by_party_by_precinct.xlsx
[ge2014]: http://www.elections.state.md.us/elections/2014/
[`hocomd-2014-precinct-council.csv`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/hocomd-2014-precinct-council.csv
[`hocomd-2014-general-election-turnout.csv`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/hocomd-2014-general-election-turnout-by-precinct.csv
[2014 general election results]: http://www.howardcountymd.gov/WorkArea/linkit.aspx?LinkIdentifier=id&ItemID=6442477038&libID=6442477030
[Howard County Board of Elections]: http://www.howardcountymd.gov/Departments.aspx?id=4294968268
[`Voting_Precincts_Cartogram.zip`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/Voting_Precincts_Cartogram.zip
[cg1]: http://rpubs.com/frankhecker/63528
[cg2]: http://rpubs.com/frankhecker/63529
[`Council_Districts_Cartogram.zip`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/Council_Districts_Cartogram.zip
[`Legislative_Districts_Cartogram.zip`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/Legislative_Districts_Cartogram.zip
[`Congressional_Districts_Cartogram.zip`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/Congressional_Districts_Cartogram.zip
[`Voting_Precincts_Deformation_Grid.zip`]: https://raw.githubusercontent.com/frankhecker/hocodata/master/datasets/Voting_Precincts_Deformation_Grid.zip