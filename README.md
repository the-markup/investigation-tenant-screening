# How We Investigated the Tenant Screening Industry
This repository contains data related to our story, "[Access Denied: Faulty Automated Background Checks Freeze Out Renters](https://themarkup.org/locked-out/2020/05/28/access-denied-faulty-automated-background-checks-freeze-out-renters)" from our series, [Locked Out](https://themarkup.org/locked-out/).

Our methodology is described in "[How We Investigated the Tenant Screening Industry](https://themarkup.org/locked-out/2020/05/28/how-we-investigated-the-tenant-screening-industry)".

The data for our analysis can be found in the `data` folder.

## Data
This folder contains the data that was used, or created reporting our story.
Supplementary files for [court case complaints](https://www.documentcloud.org/search/projectid:49060-Tenant-Screening-story-court-complaints) and [FOIAs from public housing angencies](https://www.documentcloud.org/search/projectid:49059-Tenant-Screening-story-FOIA-documents) are stored on Document Cloud. Individual court case complaints are linked from the tracking sheet below under `LINK TO COMPLAINT`.

#### data/courtcases.csv
A tracking sheet of court cases related to our story.

Data Dictionary:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CASE NUMBER</td>
      <td>The number assigned to the case in the federal court system - can be used to find the case docket on PACER. Note that case numbers will repeat in multiple rows if there are multiple plaintiffs in a single case.</td>
    </tr>
    <tr>
      <td>PLAINTIFF</td>
      <td>The person who has brought the civil case against the tenant screening company. In almost all cases, these are housing applicants who say they have been denied housing due to tenant screening errors, but in a few cases these are renters who say their rent or security deposits were raised due to incorrect tenant screening reports. Note that some cases have multiple plaintiffs that are included here in additional rows, and that some cases may have additional plaintiffs who joined on later, that are not included here.</td>
    </tr>
    <tr>
      <td>DEFENDANT</td>
      <td>The tenant screening company being sued by the plaintiff in the case. Note that there may be multiple defendants for each case, and this spreadsheet may not necessarily include all of them, despite best efforts.</td>
    </tr>
    <tr>
      <td>CASE FILE DATE</td>
      <td>The date the case was first filed in federal court - another identifier helpful for finding the case docket on PACER.</td>
    </tr>
    <tr>
      <td>DATE OF TENANT SCREENING</td>
      <td>The month and year when the plaintiff (the housing applicant) was screened by the tenant screening company. This information comes from the court complaint submitted by the plaintiff.</td>
    </tr>
    <tr>
      <td>LOCATION OF HOUSING: CITY/TOWN</td>
      <td>The city or town where the apartment or house that the plaintiff had been trying to rent is located. Sometimes this is the location of the property management company, where appropriate. This information comes from the plaintiff's court case complaint. In some cases, the location can not be inferred from the complaint; these are marked as "unknown."</td>
    </tr>
    <tr>
      <td>LOCATION OF HOUSING: STATE</td>
      <td>The state where the apartment or house was that the plaintiff had been trying to rent (or sometimes the location of the property management company, where appropriate). This information comes from the plaintiff's complaint. In some cases, the location can not be inferred from the complaint; these are marked as "unknown."</td>
    </tr>
    <tr>
      <td>ALLEGATION FROM COURT CASE COMPLAINT</td>
      <td>The Markup's brief summary of the allegations made by the plaintiff in each court case complaint.</td>
    </tr>
    <tr>
      <td>RESOLUTION OF CASE</td>
      <td>The Markup's summary of the resolution of the case as it pertains to this particular defendant. This information comes from documents in the PACER docket and is only up to date as of 4/12/20. In some cases, the resolution could not be inferred from the docket or from reporting; these are marked as "unknown."</td>
    </tr>
    <tr>
      <td>LINK TO COMPLAINT</td>
      <td>A link to the court case complaint, downloaded from PACER by The Markup and then uploaded onto Document Cloud for viewing.</td>
    </tr>
  </tbody>
</table>

Links: [Formatted](https://github.com/the-markup/investigation-tenant-screening/blob/master/data/courtcases.csv) | [Raw](https://raw.githubusercontent.com/the-markup/investigation-tenant-screening/master/data/courtcases.csv?token=ABYI6O5N6NCUGS7ODLVM2QS6X3GGW)

## Licensing
Copyright 2020, The Markup News Inc.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.