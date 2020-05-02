
# Coronavirus dashboard for Japan

[Dashboard](https://watanabe8760.github.io/coronavirus_dashboard/)

The purpose of this dashboard is to understand the situation of COVID-19 from Japanese citizen's perspective.  
The data is from
[`{coronavirus}`](https://github.com/RamiKrispin/coronavirus) package. You can also find the latest raw data in [this repository](https://github.com/RamiKrispin/coronavirus-csv).  
To reflect the latest data to the dashboard, execute a couple of commands from R console manually as below.

```R

coronavirus::update_dataset()

> Updates are available on the coronavirus Dev version, do you want to update? n/Y
Y

> Downloading GitHub repo RamiKrispin/coronavirus@master
> ...
> The data was refresed, please restart your session to have the new data available
(Restart session)

# create the new dashboard (docs/index.html)
rmarkdown::render_site()

```

<img src="https://ramikrispin.github.io/coronavirus/reference/figures/coronavirus.png" width="20%" />
