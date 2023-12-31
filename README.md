






```
r language BS28, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis PanNET metastazı, karaciğer TR, echo = (language == "TR")
## BS28 - PanNET metastazı, karaciğer {#sec-BS28 }
```


```
asis metastatic PanNET, liver EN, echo = (language == "EN")
## BS28 - metastatic PanNET, liver {#sec-BS28 }
```






```
r BS28 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS28-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS28/HE.html",
  file = "./screenshots/BS28-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS28/HE.html](https://images.patolojiatlasi.com/BS28/HE.html)





```
asis, echo = (language == "TR")

**PanNET metastazı, karaciğer**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS28-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS28/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS28/HE.html)
```

```
asis, echo = (language == "EN")

**metastatic PanNET, liver**

[![Click for Full Screen WSI](./screenshots/BS28-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS28/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS28/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS28/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS28/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

PanNET metastazı, karaciğer

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

metastatic PanNET, liver

:::

```









:::::










