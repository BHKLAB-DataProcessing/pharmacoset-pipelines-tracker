
# PharmacoSet Pipelines v2.0

A repository to track the development of the PharmacoSet Pipelines v2.0. 

The new pipelines use `processed data` as opposed to the `raw data` used in the previous version. 

The github page at [https://bhklab-dataprocessing.github.io/pharmacoset-pipelines/](https://bhklab-dataprocessing.github.io/pharmacoset-pipelines/) 
is generated using the [rmarkdown script](./PSet-Update_Logs.rmd) in this repository.

The new datasets are available in the Google Cloud buckets (links are in the rmarkdown file).

## How to build the github page

```bash
pixi run setup
```

```bash
pixi run build
```

This will create an `index.html` file which you can open in a browser to view the page.

Alternatively, if you push the changes to the repository, the github page will be automatically updated after a few minutes. 


