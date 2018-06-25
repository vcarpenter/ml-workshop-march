
# PreRequites for all the labs are below. Time needed to finish the pre-reqs ~15 mins.
## Step #0: Familiarity with Machine Learning (ML) concepts
<br>
Expectation is for attendees to be familiar:
Basic machine learning concepts: Deep Learning, Machine Learning & a rough idea of how ML can help your business
Understanding Data & its role in ML
Bring any questions, your current business problems that we can help architect via ML & Big Data during our whiteboard session
We will not be covering theory and basic definitions of ML (this is expected prior knowledge)

## Step #1: Create Google Cloud Account & Project
Please create a [Free Trial Google Cloud Account](https://cloud.google.com/free) if you don't have one
Please [Create a Google Cloud Project](https://cloud.google.com/resource-manager/docs/creating-managing-projects)

## Step #2: Enable APIs

* [Google Compute Engine API](https://cloud.google.com/apis/api/ml.googleapis.com/overview)
* [Dataflow API](https://cloud.google.com/apis/library/dataflow.googleapis.com)
* [Google Cloud Machine Learning Engine API](https://cloud.google.com/apis/api/ml.googleapis.com/overview)
* [Cloud Source Repositories API](https://cloud.google.com/apis/api/sourcerepo.googleapis.com/overview)
* [Cloud Natural Language API](https://console.developers.google.com/apis/api/language.googleapis.com/overview )
* [Google Cloud Vision API](https://console.developers.google.com/apis/api/vision.googleapis.com/overview)
* [Google Cloud Video Intelligence API](https://console.developers.google.com/apis/api/videointelligence.googleapis.com/overview)
* [Google Cloud BigQuery API](https://console.developers.google.com/apis/api/bigquery-json.googleapis.com/overview)

More on How to Enable APIs:
* In the GCP Console, go to [APIs & services](https://console.cloud.google.com/apis/library) for your project created in Step #1.
* Use the search box to look for API you want to enable.
* Click Enable.

## Step #3: Launch Cloud Datalab 
Follow [this codelab](https://codelabs.developers.google.com/codelabs/cpb100-datalab/index.html#0) (please don’t delete the VM instead shut it down or keep it running )

## Step #4: Launch the Labs
<br>
Start a notebook and run following commands:<br><br>

```
!git clone https://github.com/vcarpenter/ml-workshop-march.git  
!pip install google.cloud 
```

 
