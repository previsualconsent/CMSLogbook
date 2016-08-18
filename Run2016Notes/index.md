---
title: WR Notes for Run2016 
type: default
toc: false
---

#### Dielectron paper: [AN](http://cms.cern.ch/iCMS/jsp/db_notes/noteInfo.jsp?cmsnoteid=CMS%20AN-2016/190)

Some known issues that may be relevant to our analysis. 

 * Endcap shifted position for 3.8T was not used until Run 273726. This affects the measurement of $$\Delta \eta_{in}$$
 * L1 ID for EG H/E was too strict. Fixed from run 275656 and on. 
 * The track isolation variable of GsfElectron collection is broken for electrons with ET > 100 GeV starting from CMSSW_7_6_X. Fixed in CMSSW 8_1_X.
 * 

#### Datasets

 * [DY reHLT](https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=dataset%3D%2FDYJets*%2F*RunIISpring16MiniAODv2*reHLT*%2F*)
 * 