---
title: Dashboards
summary: Presentation of some dashboards hosted on Heroku
date: "2022-12-29T00:00:00Z"

show_date: false
reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: true  # Show author profile?
comments: false  # Show comments?

type: landing

---

I create dashboards for research and data communication purposes, some of which are showcased here. The apps use [Plotly Dash](https://plotly.com/) and are deployed with [Railway.app](https://railway.app/). 

### Visualisation of ECG data on Physionet

This app streams and plots data from the [Icentia11k](https://physionet.org/content/icentia11k-continuous-ecg/1.0/) database on Physionet, which contains data from 11,000 patients who have undergone a Holter recording (ambulatory ECG). I have a step by step tutorial on Towards Data Science on how to create this app.
<br>
{{< icon name="right-to-bracket" pack="fa" >}} {{< staticref "https://ecg-dashboard.thomasbury.net/" "newtab" >}}Run app{{< /staticref >}}&nbsp;&nbsp;&nbsp;&nbsp;
{{< icon name="github" pack="fab" >}} {{< staticref "https://github.com/ThomasMBury/ecg-dashboard" "newtab" >}}Github repo{{< /staticref >}}&nbsp;&nbsp;&nbsp;&nbsp;
{{< icon name="medium" pack="fab" >}} {{< staticref "https://medium.com/towards-data-science/building-a-dashboard-in-plotly-dash-c748588e2920" "newtab" >}}Tutorial{{< /staticref >}}
<img src="/uploads/dashboards/ecg-dashboard.png" alt="img" style="border:1.5px solid gray; padding:3px; margin:10px 0px">

<br><br>

### Restitution curve analysis
This app simulates and plots output for a model of a periodically paced cardiac cell based on properties of its restitution curve, which the user can modify.<br>
{{< icon name="right-to-bracket" pack="fa" >}} {{< staticref "https://restitution-cobweb.thomasbury.net/" "newtab" >}}Run app{{< /staticref >}}&nbsp;&nbsp;&nbsp;&nbsp;
{{< icon name="github" pack="fab" >}} {{< staticref "https://github.com/ThomasMBury/restitution-cobweb" "newtab" >}}Github repo{{< /staticref >}}
<img src="/uploads/dashboards/restitution-cobweb.png" alt="img" style="border:1.5px solid gray; padding:3px; margin:10px 0px">

<br><br>


### Covid-19 visualisation and analysis
This app displays Covid-19 cases and deaths for a given country, and computes approximations for the total number of infected cases and the contact ratio. Uses the dataset from [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data).<br>
{{< icon name="right-to-bracket" pack="fa" >}} {{< staticref "https://dash-covid.thomasbury.net/" "newtab" >}}Run app{{< /staticref >}}&nbsp;&nbsp;&nbsp;&nbsp;
{{< icon name="github" pack="fab" >}} {{< staticref "https://github.com/ThomasMBury/dash_covid" "newtab" >}}Github repo{{< /staticref >}}
<img src="/uploads/dashboards/dash-covid.png" alt="img" style="border:1.5px solid gray; padding:3px; margin:10px 0px">
