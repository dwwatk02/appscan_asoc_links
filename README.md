## Appscan Integration Repository

<img src="http://watkinsdemo.us/images/gitlab.png"/>
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>ASOC</td><td><a href="https://github.com/jrocia/Integration-ASoC-and-Gitlab">Integration-ASoC-and-Gitlab</a></td></tr>
    <tr><td>ASE (DAST)</td><td><a href="https://github.com/jrocia/Integration-ASE-DAST-and-Gitlab">Integration-ASE-DAST-and-Gitlab</a></td></tr>
    <tr><td>Appscan Source</td><td><a href="https://github.com/jrocia/Integration-AppScanSRC-and-Gitlab">Integration-AppScanSRC-and-Gitlab</a></td></tr>
    <tr><td>Appscan Standard</td><td><a href="https://github.com/jrocia/Integration-AppScanSTD-and-Gitlab">Integration-AppScanSTD-and-Gitlab</a></td></tr></table>

<img src="http://watkinsdemo.us/images/jenkins.png"/>
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>Official Jenkins plugin</td><td><a href="https://plugins.jenkins.io/appscan/">plugins.jenkins.io</a></td></tr>
    <tr><td>Appscan Source->ASE</td><td><a href="https://github.com/kevinfealey/appscanenterprise-publisher">appscanenterprise-publisher</a></td></tr>
</table>

<img src="http://watkinsdemo.us/images/ado.png"/>
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>Simple Azure task that can be added to ADO pipeline</td><td><a href="https://github.com/yopez83/Azure-Task-AppScan">Azure-Task-Appscan</a></td></tr>
</table>

<img src="http://watkinsdemo.us/images/circleci.png"/>
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>ASOC and CircleCI</td><td><a href="https://github.com/antonychiu2/CircleCI">CircleCI</a></td></tr>
</table>

### Bitbucket Integrations
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>ASOC and Bitbucket</td><td><a href="https://github.com/HCL-TECH-SOFTWARE/bitbucket-asoc-sast">bitbucket-asoc-sast</a></td></tr>
</table>

### Docker Integrations
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>Appscan Presence </td><td><a href="https://github.com/jrocia/AppScanPresence-Dockerfile">AppscanPresence-Dockerfile</a></td></tr>
</table>

### Dradis Integration
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>Dradis framework add-on for importing Source assessment results</td><td><a href="https://github.com/dradis/dradis-appscan">dradis-appscan</a></td></tr>
</table>

### IBM Resilient Integrations
<table>
    <tr><th>Description/Technologies</th><th>Link</th></tr>
    <tr><td>ASOC->AIG->IBM Resilient</td><td><a href="https://github.com/IBM/asoc-devops-tooling/tree/master/appscan-issue-gateway-resilient">appscan-issue-gateway-resilient</a></td></tr>
</table>

### Utility, helper, wrapper scripts
<table>
    <tr><th>Description</th><th>Keywords</th><th>Link</th></tr>
    <tr><td>python wrapper script around SAClientUtil</td><td>SAST,ASoC,SAClientUtil</td><td>https://github.com/cwtravis/python-saclient-wrapper</td></tr>
    <tr><td>bash script to export issues from ASoC and import into ASE</td><td>ASOC,ASE,APIs</td><td>https://github.com/jrocia/ImportAppIssues-ASOC-ASE</td></tr>
    <tr><td>- .bat wrapper around SAClientUtil<br>- python script to download applications from ASOC</td><td>ASoC,SAClientUtil</td><td>https://github.com/jrocia/ImportAppIssues-ASOC-ASE</td></tr>
    <tr><td>python wrapper script around Appscan Issue Gateway</td><td>AIG,JIRA,Azure DevOps</td><td>https://github.com/cwtravis/AIMG_Client</td></tr>
    <tr><td>python script to parse Appscan Standard xml report files and create spreadsheet with issues combined and sorted by severity</td><td>Appscan Standard,reporting</td><td>https://github.com/Bruk0ut/appscan-xml-report-parser</td></tr>
    <tr><td>python helper script around various ASOC functionality</td><td>SAST,DAST,ASoC</td><td>https://github.com/ntinvo/appscan-automator</td></tr>
    <tr><td>powershell script that takes inputted list of URLs and kicks off Appscan Standard scans, specifically for Log4j vuln</td><td>Appscan Standard,DAST,Log4j</td><td>https://github.com/jrocia/Search-log4Jvuln-AppScanSTD</td></tr>
    <tr><td>python script to take an inputted list of URLs and scan for Log4j</td><td>ASOC,DAST,Log4j</td><td>https://github.com/cwtravis/asoc_dast_spray</td></tr>
    <tr><td>python wrapper script around various ASE functionality</td><td>SAST,DAST,ASE</td><td>https://github.com/sperlis/ase-apis</td></tr>
    <tr><td>python script allowing you to run concurrent appscan prepare commands</td><td>SAClientUtil,SAST,ASOC</td><td>https://github.com/m3ssap0/massive-appscan-prepare</td></tr>
    <tr><td>python script to scrape Support pages for SAST language support</td><td>SAST,Appscan Source,ASOC</td><td>https://github.com/gledonne/appscanlangs</td></tr>
    <tr><td>scala app that takes inputted .ozasmt file and import findings into mongodb</td><td>Appscan Source,.ozasmt</td><td>https://github.com/blackboard/appscan-source-parser</td></tr>
    
</table>



### Vulnerable code examples

<table>
    <tr><th>Description</th><th>Link</th></tr>
    <tr><td>Java API application</td><td>https://github.com/coadaflorin/appscan_api_Demo</td></tr>
    <tr><td>ABAP</td><td>https://github.com/sreejuonline/AppScan-abap-code</td></tr>
    <tr><td>Webgoat .sln file scanned via Github Actions</td><td>https://github.com/antonychiu2/ASoC_Demo</td></tr>
    <tr><td>Apex app scanned via Github Actions</td><td>https://github.com/cwtravis/asoc-apex-demo</td></tr>
    <tr><td>Java Altoro app scanned via AppscanSrcCli, optionally gen report and publish to ASE</td><td>https://github.com/antonychiu2/AltoroJ</td></tr>
    <tr><td>A number of vulnerable .cpp applications</td><td>https://github.com/atxsinn3r/VulnCases</td></tr>
</table>
