---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Statistical–Dynamical Forecasting of North Atlantic TC Activity on the Subseasonal Time Scales"
event:
event_url:
location: Seeon, Bavaria, Germany
address:
  street:
  city:
  region:
  postcode:
  country: "Germany"
summary: "Forecasting tropical cyclone activity, a complex numerical weather prediction model was shown to be beaten by simple climatology forecasts, which in turn are outperformed by simple statistical models."
abstract: "Predictions for individual tropical cyclones (TCs) made by operational forecast centers for lead times of a few days rely heavily on numerical weather prediction (NWP) models. In contrast, seasonal predictions of TC activity are much more strongly based on statistical models. We here explore the use of combining NWP forecasts and statistical methods for subseasonal lead times and employ this combined statistical-dynamical approach to forecast spatio-temporally integrated TC activity metrics (e.g. accumulated cyclone energy) in the North Atlantic Ocean. We exploit the ECMWF’s subseasonal to seasonal (S2S) 1998-2017 reforecast ensembles to derive relevant NWP-based predictors, such as Hovmoeller diagrams filtered for convectively coupled equatorial waves, African easterly waves, and the Madden-Julian oscillationin the tropical wave channel, or sea surface temperatures. In addition, extratropical waves impact TC activity in the North Atlantic Ocean, in particular when elongated troughs intrude equatorward associated with (anticyclonic) Rossby wave breaking. Simplified representations of extratropical Rossby wave breaking are therefore considered as well. This combination of tropical and extratropical predictors allows to cover a broad spectrum of TC life cycles, ranging from tropical-only to strongly baroclinically influenced TC genesis, and including tropical and extratropical transitions. The predictors based on NWP forecasts are then amended by two types of statistical approaches. First, a multilinear regression model is trained to capture the linear relationships between the dynamical predictors and the forecasted metrics. But because TC genesis and activity are associated with several nonlinear processes (e.g. wave interaction and breaking, convection), we develop a neural network and examine putative improvements due to the nonlinearity inherent in that type of statistical model. Both statistical models are validated and compared against the raw, dynamically based NWP forecasts, which serve as benchmark and lay the foundation for skill scores. The skill of the trained model to forecast TC activity will be assessed using leave-one-out cross-validation with the IBTrACS and ERA5 reanalysis data. As some predictors are subject to systematic biases, we further investigate whether an implicit bias correction carried out in the neural network is sufficient or if a pre-processing of the predictors is necessary."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-10-03T09:20:00
#date_end: 
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-06-05T14:26:17+02:00

authors: [Michael Maier-Gerber, Andreas H. Fink, Michael Riemer]
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
