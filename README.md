# GoogleAPI
# Check Lists 1+2

## My API Key
AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

## Embed My Maps to a web page
## 1. JavaScript API (HTML Interactive Map):
https://RaghadEstanbouli.github.io/GoogleAPI

## Example URL sharing:
## 2. Directions API (JSON Return)
https://maps.googleapis.com/maps/api/directions/json?origin=Dubai%20Mall&destination=sama%20Tower%20Abu%20Dhabi&&waypoints=via:Dubai+Mall&key=AIzaSyCko5oY9-5y5yklqDx9tDnLkUzgPgXWeys
### Result: 

```json
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJB1zIKShoXz4RnbaTPPup7aU",
         "types" : [ "establishment", "point_of_interest", "shopping_mall" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJg2f69W5mXj4RsxHsz89X3_E",
         "types" : [ "establishment", "premise" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 25.2007922,
               "lng" : 55.2938055
            },
            "southwest" : {
               "lat" : 24.4222796,
               "lng" : 54.3597075
            }
         },
         "copyrights" : "Map data ©2021",
         "legs" : [
            {
               "distance" : {
                  "text" : "148 km",
                  "value" : 147803
               },
               "duration" : {
                  "text" : "1 hour 41 mins",
                  "value" : 6086
               },
               "end_address" : "Abu Dhabi - Zone 1 - Abu Dhabi - United Arab Emirates",
               "end_location" : {
                  "lat" : 24.4832534,
                  "lng" : 54.3607188
               },
               "start_address" : "Financial Center Street, Along Sheikh Zayed Road, Next to Burj Khalifa - وسط مدينة دبي - دبي - United Arab Emirates",
               "start_location" : {
                  "lat" : 25.1994485,
                  "lng" : 55.2752351
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 253
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 25.2005014,
                        "lng" : 55.2773622
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eSheikh Mohammed bin Rashid Blvd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qwxxCg}jpIEe@UiBGSE]CICOIWCEGQQ]?AMQKOUWUW_@[QM"
                     },
                     "start_location" : {
                        "lat" : 25.1994485,
                        "lng" : 55.2752351
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1895
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 248
                     },
                     "end_location" : {
                        "lat" : 25.1916209,
                        "lng" : 55.2927272
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFinancial Center Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD71\u003c/b\u003e (signs for \u003cb\u003eBusiness Bay Cr\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "c~xxCojkpIWs@KSMSCIC[?G@[Vm@`AcCpEkKpBuEp@}A|AeDf@qAHO`@aA|L_YHUh@sAFKJYN]BGL[Na@BGLYHUFKTe@HOLQHKV[f@g@HI|BwBZWnBkBt@k@|@o@hAm@"
                     },
                     "start_location" : {
                        "lat" : 25.2005014,
                        "lng" : 55.2773622
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 607
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 25.1863237,
                        "lng" : 55.2938055
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eFinancial Center Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD71\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "sfwxCqjnpI^Uj@YRGb@MtDkArASNA@?TCJA`@GHAXAXAtBGb@AZAF?nDIrCE"
                     },
                     "start_location" : {
                        "lat" : 25.1916209,
                        "lng" : 55.2927272
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "19.4 km",
                        "value" : 19407
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 790
                     },
                     "end_location" : {
                        "lat" : 25.047312,
                        "lng" : 55.1966551
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eJebel Ali\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE44\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAbu Dhabi\u003c/b\u003e and merge onto \u003cb\u003eE44\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "oevxCiqnpINDL?dA?hB@j@@b@@J@D?PBPDNDJDRHB@\\Rf@f@Vb@NXL`@Jf@Hz@Dd@JnATxBVfDVbC\\xCF^FR`@nFPjBFr@Fr@?@HjAFx@BZDVL~@XxALp@H`@t@dBhAfCv@dBZt@fAbCdAbC@BrAnC`@r@b@j@R^p@nAb@v@fAjBt@hAfA`Bf@r@zAtBvBvCpAfBtApBj@t@nBdCx@bAfArAXZXZPRDFZZNNHHRTDDXZXXXZZXJJLLXZZXPPFFZXXXZXZXHJNLZXZVZXXXZXZVZXZXXV?@ZXZVZXXXZXJHNNZVXXZXZXZXNNHFLJ?@LJZXZXZXXVZXZXZXXVTR~CnClAhApBfBjB`BxCjCvAhA`BpAzBfAhAf@rAd@jA\\zBl@bBTxBXJBVB\\DXBl@Bl@@pEFrJR|AD`KLnC?jBBfBB`D?dDD`HFfABh@@pBBdC@`A?tCFb@@j@?`CBxDB@?jCFfBD~AF~@DrAHxBPjCVtAPjEh@H@XD`@H`BTrATtCh@~EjARFpCp@vA`@PFn@PbBj@@?`@LjA^hBn@vAj@pBx@rMfGt@`@zEhChGvD~AdAfDhChAz@zBfBpD|CnDrC~CfCdBzAfA`AbDrCj@f@v@p@lEvDbCpBbA|@bA|@z@r@n@l@bFfEZXZVFFRPZVZXt@n@@@ZVZVZXZV\\VLLLJXVZXv@p@ZXZXZVZXXVRPFFZXZXZVZXXXZVHH\\ZdHdGnIlHxBfBrIbH|BrBt@n@hB|AlCzBdA~@vCfCxBlBdBzA`@\\p@j@bAz@zBpBfBzA`BtAbDrCjC|BxCnCnAhAh@f@hDtCbBxANLZVlEvDnGlFlAbA~F`FzDhD`J|HZX@@rExDxIrHfBzAtJhI|BjB~ChC~ArA~ExD`CjBpBdBf@b@rAhA~AtA^\\ZVv@p@nExDZXlEtDPPZVZVtCdCbBvAnD|CrBjB~BrB|DhDtE|DnB`BvD`DlB`BhCvBdA~@nAlAVVPPVXPRb@d@jDfD~BlBb@ZzBvAbAh@hBbAhB|@xAl@f@PB@dCx@tA`@`@HlDr@v@LjAPj@HtBVfAHnAHhADL?~@DnABlA@lA?zCBlBAdCKnAGjAIh@E`AOz@Oz@OvBo@hC}@TIb@ShCeAxAu@"
                     },
                     "start_location" : {
                        "lat" : 25.1863237,
                        "lng" : 55.2938055
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1091
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 25.04171,
                        "lng" : 55.1904111
                     },
                     "html_instructions" : "Take the \u003cb\u003eE311 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSh Mohammed Bin Zayed Rd\u003c/b\u003e exit toward \u003cb\u003eDWC Airport\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAbu Dhabi\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "u`{wCcr{oIlCeAp@Uj@MXE^EVAh@Ar@LVFb@Jh@Lh@Rl@Rl@TXNPHRNb@\\\\^PPNRPVLXJVJZJ`@T`Av@zETfAr@jFNhARbBJr@Nz@T~A@F"
                     },
                     "start_location" : {
                        "lat" : 25.047312,
                        "lng" : 55.1966551
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3150
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 25.0255838,
                        "lng" : 55.1649213
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e and merge onto \u003cb\u003eSheikh Mohammed Bin Zayed Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE311\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "u}ywCakzoIFZJd@TbAl@jCZpAVdARt@fAdC@Dv@lCr@xBVz@rAhDzDfIj@|@`@t@pFxJvCzET^xBlDfBpCjCdE~JhPzCrE|BrD|@vApFtIjDxFzGpKh@v@\\d@p@|@j@v@zAjBj@j@"
                     },
                     "start_location" : {
                        "lat" : 25.04171,
                        "lng" : 55.1904111
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1714
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 25.0186306,
                        "lng" : 55.1507801
                     },
                     "html_instructions" : "Take exit \u003cb\u003e22\u003c/b\u003e for \u003cb\u003eAl Yalayis St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eD57 W\u003c/b\u003e toward \u003cb\u003ePJA Port\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{xvwCwkuoIHXBDHLXf@zAbB~BnC~@`ANNhDhCrIxFn@`@dApANTNVHTP`ARbBPlB\\`E`@zEb@~Db@rFDf@H~@Hn@`@tBf@`BbA|H@HFT"
                     },
                     "start_location" : {
                        "lat" : 25.0255838,
                        "lng" : 55.1649213
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 km",
                        "value" : 3928
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 152
                     },
                     "end_location" : {
                        "lat" : 25.0177381,
                        "lng" : 55.11197439999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eD57\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "mmuwCksroIb@pEf@nGZ~Df@vFBPHbAVzBVnBj@lFPjCT`E`@lVJzLBrf@CnHGfJGpDOnIAd@MhGIpFEz@IbFKrDAZAJAZQhGGnDO`IAf@UbL"
                     },
                     "start_location" : {
                        "lat" : 25.0186306,
                        "lng" : 55.1507801
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 810
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 25.0181294,
                        "lng" : 55.1039492
                     },
                     "html_instructions" : "Take the ramp to \u003cb\u003eE11\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{guwCy`koIKnBO`FAf@Ad@Af@?f@Af@Af@Ad@?f@AP[jSGvG"
                     },
                     "start_location" : {
                        "lat" : 25.0177381,
                        "lng" : 55.11197439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1145
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 25.0178274,
                        "lng" : 55.0946589
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue toward \u003cb\u003eE11\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "ijuwCunioII~@Gd@G\\IRMZQj@GNKPSZg@r@_BlBgB~Bs@vA[x@UlAG^Ib@?@Cf@Ad@APAb@Cl@@^?PBTJbABLN|@@DJd@FRPl@Pf@b@lAn@`Ad@l@NPv@~@bCfBv@`@~@`@"
                     },
                     "start_location" : {
                        "lat" : 25.0181294,
                        "lng" : 55.1039492
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "69.1 km",
                        "value" : 69078
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2460
                     },
                     "end_location" : {
                        "lat" : 24.5535201,
                        "lng" : 54.6945405
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e and merge onto \u003cb\u003eE11\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "mhuwCstgoIZLdAX~AVhAJl@BD?z@C\\?b@C`@C\\CDA^EbAS@A`Ac@jAc@RKl@]l@a@z@k@x@m@\\UROf@Yb@Qb@O`@KXEb@GZEhACfGh@rCTpBJ~@FJAb@Ev@Dj@@b@ARCNArCVnFh@b@D~PbBjDPbCRvF\\hCX|ALtCVvBRhDZdHp@lCT`CRvBRzGn@|ANzE`@nD\\xGp@|@HzE`@bEZ~BTbBR~C`@jATtBZnDr@rBb@z@Rl@NhATnEhAdBf@|DnAfJfDlH~CfD|AlB|@\\RxBjAxGdD~DjB^Pt@^pHtDvCxAHFxHtDhEtBfBz@^Rz@b@pBdAbKhFhDlBpBfAvCnB`BjAlBrAfBtAbCrB~CxCjBlB|AdB`E~E|A|BzCpEj@`Ar@hApAbCnAbCVf@t@|AjAdC@@~@hChB|Et@zB\\pAdAtDrBlIxCzLr@rCxAbGxAbGLb@r@rClEvQz@jDtB~IbAzDDTh@tBdC~JhArERv@VhALd@nAjFfApEJb@^|ArCpL`H`YfAnEvBxIl@bCLb@ZpAH\\pDzNrBpIf@tBhClKbGfVd@nBh@tBzBjJtCvLbEtPd@jB|BnJpBdILb@dBhHtAzFf@tBrBlIr@rCdElQvAjFXjAxB~In@hCzAjGz@hDvA|FrBrIlCrKbBjH@DZnA~@vDtCfLhBrHdAjEb@bBjBzHv@bD|@nDfDlNrAjF`AvDJd@b@dBjAjFdBzGlBtI~EdRdBhHxEtRj@~BvAnF|@jDlBrFzAlEbBhEp@lBx@nBv@dBjC|FfB~CpCbFl@`A~AlCdD`FzBhD|DbFfCzClBvBlGtGX\\lAlA~EjEpBbBhA|@`BpArAz@tCxBhBjAhCfBjEnCpGbEbF~CzA`AhEnC|CnBxA`AHFNJFD@@d@XfFdDrFjD`DtBbFhDrDhCf@\\ZXpA~@j@f@v@t@PNNNpBfBzBtBj@l@bAdAXX|FjG^`@`BdB`MtMpBtBrMjNlH~HvD~DbP`Ql@r@`EjExA|AjCpC|BdC|A`BzIjJxCbD`CfC|C`Dr@t@XZfBlBXZXZr@t@r@v@vC`D~AbBbChCjAnAvD~DtE~EXXPR`CdCbBfBvCrCdCxBtAjAdBxAlD~BpBrAzCjB\\TlBhAvBtApFhDdC`BnEpCvEtC|ItF`I~EvBrA`LbH\\T|GfEfJ|FnBnAvChBvJfGNH^R~HbFbCxAfDvBlIhFvD|B\\T~PpK^Tx@f@rHvEdLhHFB`HhEjC`B|EzCxA~@~D|B`EpBn@\\n@X^PlBz@tCjAfKbE`Bp@tBt@zCnAdGbCbDpA`A^rHzCtBz@jBn@zJ~D`C~@dFvB~@^@?B@RHfDrA`DpAlBr@~B`AzN|F|Al@hFrBlDtAjEfBlCdAzB|@|ElBvElB~@\\hDrAtAj@tChAvBz@|CnAnCdAvClA`DnAfBt@tEhBt@XfCbAh@VpDvA|ClAdCbAvBx@vB|@VJpCfA~B~@jAf@nBx@lBv@x@^pAl@fCnApBhAnC~AVNz@j@RLrE|CxCtBpCjBrDhCtA`ApE|C\\VxDfCrDfCdD|BlAx@lBrAvE`DtDhCdDzBlCjB\\TtFxD`LzHTPvR~M\\TdItFvBxAZTrCnBbJhGfAx@ZTz@h@tBvAzCtBnKlHfAt@rBvA~HrFjBtAxBdBbAz@RRfB~AbCdCtC`DfEfF`@d@~@jA~ArBxCrD`BnBV\\X^z@dAfEdFzDtE~C~DtAbBxE|FV\\LNtA`BrCjDf@l@pBbC`CxCnCfD|BpC@@rE|FxBlCzAfBNPVZn@x@bCzCdCxCrCjDpDlEjFrG|@fAfEjFvIlKVZX\\PTbHtIjAvAx@bAfBvBj@r@n@x@HJd@l@NP`AjAnCdDdC|CvExFx@`AHJbBjBvAxArAtA|EjEpCvBvCvBvBzAxBxAfCfBTNFDbErCpGjEjEzCfHzEjExC`FhD|F~DzLnIbCbB@?LJ\\RfBnAjBpAdIxFvElDlClBFFp@d@\\V|DvC~C|BfBrA|FdEjEzC~AhAbD|B~CtBbDzBjKjH`FjDdFhDpDhC|B|A|BbBbBhArClBlAz@fHdFjD`CdD|BjCpB`ClBfCrBlItH|BxBvBlB~DpDHHj@h@ZX~AxAjAdA`CzBdCzBzFpFv@t@xBvBrBfBfEzDbCzBZXNLvHdHl@h@xDnDLLdItHbGrF`BzAJH~ElEhD`DrFhFvDnDvApAlBdBZXpAjAjBfBnAhAnBhBv@p@rDlDvDlDpFbFdFtEb@b@lAjArCfCn@l@XX^`@p@j@rAlAbDtCZVVTrDlDlCbClAfAzCrC~ApAz@t@jChBlAt@rBnAz@f@dAj@vBdAJFvDfBxGbCzBx@pDnAjAd@r@VlBj@nRrGNDdOhF`AZvCbA`@NhC|@pQdGfItCfA`@`GrBzKxDdGtBf@PzAh@jA`@nBr@fA\\vExA`ExA`AZbFdBxHnCnGvBdDjAdCx@hFfBtIvCzBv@`FdBlBp@`@NxDxAdBn@t@V~@ZjA^lDlA^NPFjBj@bEjA~@T|A\\nAV^HtATz@JdC^bBLtAJ~BPtBL|@Db@BdCLzDNbJh@~Hb@vG^fH\\N@dAB~BNrCPvBJ@@lAFnEV|G^dJf@fBJpGd@~DRnFT|CN"
                     },
                     "start_location" : {
                        "lat" : 25.0178274,
                        "lng" : 55.0946589
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "40.6 km",
                        "value" : 40641
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1442
                     },
                     "end_location" : {
                        "lat" : 24.4808702,
                        "lng" : 54.38661519999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue on \u003cb\u003eAl Shahama - Abu Dhabi Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSheikh Zayed Bin Sultan St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eE10\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "orztC{oylIzH^hBHp@Fp@DpAHdBJbAJ^Fx@LrAVj@Lr@RdAZz@XPHh@Rf@Vl@Xf@VXPd@X\\T^VfAx@dA|@~@x@XXd@f@h@p@d@j@fBdC`@n@zAtBx@dAtAbBfAnA~@dAhCdC|@t@ZXl@h@pAbAp@f@dAr@xAdAlAv@|@n@TN|@n@`C`BjAv@jDbChAv@tB|AZTfD|BxHtFrCrBfCdB^TxCvBjChBxA`AlDjC`FhDrBzA|@l@bAt@jBnAzAdAfFrDvAdAdBjAzEhDjCjBlBrAtCrB~BbBrAbAdC~AfBpAbDzB|AfAJHbBlA`DxBtEdD~CxBpCpB\\Tr@h@hEzCzDlCvDlCjDhC~B|AnBrAxB|AnFzDxEbD|HxFRJfBpAZT`EvCzJdHj@`@ZTt@h@bCdBjFtDjClBxEhDl@`@\\VzAbAtFpD`BjAz@j@nCnBvF|DpCnBnCnBpClBVPpA~@vF~Dp@d@LHnA~@@@TN\\TpIbGpA~@B@ZTd@^pEzCzG~Ed@ZxAfApBvAxF`ElBtAvCrBb@XpCnBjBrAjFrDpA|@LJd@Z`An@zCvBhD~Bp@f@jGjE`An@vA`ApBjA~Av@\\Pz@^t@^nBv@@?jDpAbBd@tBj@`Bb@nBh@bBb@NFzF~ApBj@bCz@~Ap@dDvAj@X~BlAl@Z`CvArBxAv@n@f@\\bAv@lAdAbBfBXVFFl@p@HJtA~At@`ABDpA|A?@JNHJFJl@x@hAfBp@lAFJx@`B|@hBf@lAp@`BnAlD\\bAX`AZjANn@Tv@XnAl@|C^hBRjAb@|BZbBr@pDXbBp@nDZ|AxC|OBRpA|G|A`Id@dCHf@\\hBJd@dAxFBJBPDL`AjFvDjSzAfI|BjLVnAfAbGLr@|FzZrAhHpDpRt@|DrAlHTjAHb@^pBn@`DjCvNf@dCrBbL|BxLlAjG\\nB^pBNp@VrAVzAbAjFxC`P`AjFlArGX~AnCbOt@vDt@zD`A`FHb@dAzFx@jEt@`EjB|JjCdNj@`D\\hBJd@l@~CP`ARhAJd@tBdL\\bBzAhI`@vBZbBVpAtAlHjBxJd@bCRbAxAdIbAhFX`BfBjJdAjFrAlHv@lEv@`E^tBp@pD`@nBFf@TvAPtAHv@Fr@HfABb@F|ADhA@vA?fAAdBO|EC^GtCGbEC|CAzA?v@AjA?BAlA?L@`ABpN@lA?bD?H?f@?R@dA?~B@Z?X@~D?d@@d@?~A?D?lC?`B?T?VAf@?f@Ad@?f@?NAV?f@Ad@?f@AR?RAf@?d@AV?NAf@?d@Af@?f@?HA\\Ad@A\\AHCf@AT?NCf@A^CZEhAUvEOhC]lF_@|EEj@?@CJ?BKnAO`BUfCa@xECREd@Ef@WlCC`@Gj@Y`D_@hDUdCCRARGd@Ed@OhBUvCIfAQjCEf@Cd@CVSbCADEf@C`@ABEf@Ed@_@nEKvAKlA]`EGx@CRYfDSfBIv@QfACLCNCNOx@M`@I^K\\a@pAQb@GTWh@CFEHMXCFQ^?@S`@A@EFMTEJMREFOTOVEFW\\GHKNABW\\W\\UZA@U\\W\\W\\iBhCU\\W\\eAxAU\\W\\eAzAeAxA]f@aAjAq@v@{AlBgCvDcAvAoExGwB|CoAfB}B`DQXoAdBm@~@OTW\\OVEDS^i@|@mAnBsAdCYl@[j@A@?@CD}@dBc@bA{@fBCBq@`Bc@fAa@bAa@dAO`@GNIP}@fCq@rBUv@Sp@eAnDK\\s@nC{@zCgApEOn@aAnEs@zDy@|EqAtGaAtFERMv@Kb@Id@m@fDwA`IIf@q@nDOr@{@vESfAMx@CZOtAEb@CV?NCb@A@Af@APAz@A\\@zA@~A@z@@d@@b@DpABt@XrENbBBRXpCVxBP`Bp@xGLbAZxCd@rEZnC^hDBf@FlABf@@bB@P?t@Aj@Ah@Ev@IvACXEf@E^CZIf@If@If@Kf@Qn@}A|FMf@eBhGa@xAkBbHoC`Kw@pCqBpHERSr@q@bCUv@Sx@Ql@GNOd@MZELSh@Sd@Wj@ABSf@_BjCuAnB_BhB[Zg@d@u@l@i@d@e@^g@\\}@l@{DxBoAr@yEjCwElCA@m@\\uAv@c@TKHcAh@yCbB}@f@{DtB}@f@oEdCaAh@yDxB}@f@YNwAx@}@h@_@RwCbBA?yDvBaDhBuAv@]R_@RaEzBoAn@cDlB{BpAULcCvAyC`B_@REBWN{@d@oAr@OH}@f@gCvA{A|@}Az@UNeDlB]R}Az@{BpA{@f@_@R_B|@wC~A}C`BWP]R]R_@TwDxB]TwChB_B`AoAx@"
                     },
                     "start_location" : {
                        "lat" : 24.5535201,
                        "lng" : 54.6945405
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 617
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 24.4852294,
                        "lng" : 54.382879
                     },
                     "html_instructions" : "Take the exit on the \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "mlltCkk}jICNADOPqA`Ak@`@y@l@qCpBk@b@w@n@k@d@MJ[VkA`AmCzBsBbB"
                     },
                     "start_location" : {
                        "lat" : 24.4808702,
                        "lng" : 54.38661519999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 254
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 24.4869175,
                        "lng" : 54.38119469999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ugmtC_t|jIGLUZWX}@v@_BvAONe@b@u@t@QR"
                     },
                     "start_location" : {
                        "lat" : 24.4852294,
                        "lng" : 54.382879
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 286
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 24.4855939,
                        "lng" : 54.3789782
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003e9th St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Falah St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOld Pasport Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "grmtCmi|jIYTLVh@z@dBnCh@z@zAbC"
                     },
                     "start_location" : {
                        "lat" : 24.4869175,
                        "lng" : 54.38119469999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1676
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 245
                     },
                     "end_location" : {
                        "lat" : 24.4762982,
                        "lng" : 54.3659542
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003e9th St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Falah St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOld Pasport Rd\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}imtCs{{jIPTPVR^\\d@dBlC\\h@dA~ARVTVZf@@@`@r@l@lAPV\\h@zBlDb@r@hChETX^n@j@`A~AfCtAxBV^bB~B^`@p@jAPZ`@|@lAlBlAtBdAdB\\d@`DvEhAbBX`@NR"
                     },
                     "start_location" : {
                        "lat" : 24.4855939,
                        "lng" : 54.3789782
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 585
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 24.4797423,
                        "lng" : 54.3618581
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e18th St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAbu Dhabi - Al Ain Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSheikh Rashid Bin Saeed St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{oktCejyjIAN?L@NBX?VARKd@iAlAa@`@cCfC[ZyDvD?@YVA@gA`A{@v@_At@"
                     },
                     "start_location" : {
                        "lat" : 24.4762982,
                        "lng" : 54.3659542
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 377
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 24.4823979,
                        "lng" : 54.3597075
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "keltCspxjIs@GoA`AQRWRk@h@UTGFCFCHmA~@c@\\{AtAeA|@"
                     },
                     "start_location" : {
                        "lat" : 24.4797423,
                        "lng" : 54.3618581
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 186
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 35
                     },
                     "end_location" : {
                        "lat" : 24.4837788,
                        "lng" : 54.3605823
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAl Mukhallas St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Mulhlis St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_vltCecxjIk@?MCSE[GMCQG[QKIQUq@{@QUKK"
                     },
                     "start_location" : {
                        "lat" : 24.4823979,
                        "lng" : 54.3597075
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "63 m",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 24.4833742,
                        "lng" : 54.3610087
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAl Mukhallas St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAl Mulhlis St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s~ltCshxjIBIx@y@RQ"
                     },
                     "start_location" : {
                        "lat" : 24.4837788,
                        "lng" : 54.3605823
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 24.4832325,
                        "lng" : 54.3608922
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 1st cross street onto \u003cb\u003eAbu Al Bukhoush St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a|ltCikxjIZV"
                     },
                     "start_location" : {
                        "lat" : 24.4833742,
                        "lng" : 54.3610087
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20 m",
                        "value" : 20
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 24.4832534,
                        "lng" : 54.3607188
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eAbu Al Bukhoush St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e{ltCqjxjIC@CD?@?F?D?@BF"
                     },
                     "start_location" : {
                        "lat" : 24.4832325,
                        "lng" : 54.3608922
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "qwxxCg}jpI{@sFcBiCuAqBUaAlHyQhHkP`Q_a@zAoDdGkGlHuFbCeAzGaBlAOtP_@nHL~@T|AfA`AfCp@jHxCh[jAhKvC`I`FbLlIfOlQ|VvNnP`VvTnHxGlVdT|ExC|ClAdLzB|Vr@ll@h@pSTdXl@nUlChW`GrExAfW|KzRhL~OjMr]~YrShQbLtJ|sAxjAhhAr`AvbAfz@xv@zp@fSlQ`JnIlI`FnF~BjLxCtOzAjHJ~MQrFo@rIgCtKuEvCo@lCPdD`AlB~@bBbBv@dBnBfKrClSnAtFnCrIdChI|IdRxObXnWta@n^hk@`IhKxJjJbKzGtAfB~@rEtBjU|@jKhAvEdAfInBvTlAhMjBjTl@hd@?bp@a@n[g@zW}@z_@y@z\\{@pc@aCjFgElFoApCg@rCGxFxAdHhCnEzDfDvBbAjGjAlC?hBMfD_AzDoBfD_CpCgAbDWlQrArC?zEN~^dD`i@rEfl@nF|Q|AdMfBlKzB|PvEtSfItGzCpRpJtc@pTpQfJtOpJxNvLhNpPlI`NhFnK`FdNpJp_@hTv|@|Jba@rj@f}Bt|AxmG~m@tfC~I|YfGlOrLbU~P|V|OfQhNzL`g@n\\`u@lf@pNhMdn@jp@fsArwAbRdS|\\h]zMxJ~K`Hx}@`k@baBvcA`o@t`@`NfHjT|Ihg@dSh\\rMtvAvj@`bAp`@~UzJ`LhG|LlI~c@zZpc@pZh|AneAxSfObItHrXp\\bv@d_AxfBbxBxGfH~RvOhf@n\\reA|t@vvAjbAle@x\\|]p[zz@lw@dcAd_Adu@br@vMpLhKdHdG`D~VtJlq@lUp`An\\xrAjd@rYdKjIpCpLvCvHjAnLx@fs@rDhsAhHbPnAxKdD`JbGhDlDjGvIvG~HpG~FbOlKbcAfs@p{@rm@rnCzmBxw@dj@hq@|e@xv@ni@jHtDrIhDl[vItL~EbLzGdLdK`GnHxI`PxDtKzAbG`Hz^lZr_B`hAn`Gxv@ddE~CjTRbHUjLYhXFxZB`_@M`OaC~c@qCn[iEjg@gE~d@oBnHmAtCgEvGgStXia@nl@{G~LmGdO}FtQgElPaG~Z{F|[yDrUQ`Fl@|SrD|]dBtPNjFc@|JkDpOaVx{@aA~BiHlKcDtCgIdFwTdMa^|Rim@`]gb@~U}i@n[gBhBcHdFcNhLiIbIKl@nCjEhDlF`ItLjLpRrLnQfOlVpBhDDnAMx@kBnByI|I_DrC_At@s@GaBtAaBzAyBnBaDrCy@CoAYkBmB]a@|@cAn@DGF?PBF"
         },
         "summary" : "E11 and Al Shahama - Abu Dhabi Rd/Sheikh Zayed Bin Sultan St/E10",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
## 3. Places API (JSON Return)
https://maps.googleapis.com/maps/api/place/details/json?place_id=ChIJS-JnijRDXz4R4rfO4QLlRf8&fields=name,rating,formatted_phone_number,opening_hours,price_level&key=AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

```json
{
   "html_attributions" : [],
   "result" : {
      "formatted_phone_number" : "04 888 8888",
      "name" : "Burj Khalifa",
      "obfuscated_type" : [],
      "opening_hours" : {
         "open_now" : true,
         "periods" : [
            {
               "open" : {
                  "day" : 0,
                  "time" : "0000"
               }
            }
         ],
         "weekday_text" : [
            "Monday: Open 24 hours",
            "Tuesday: Open 24 hours",
            "Wednesday: Open 24 hours",
            "Thursday: Open 24 hours",
            "Friday: Open 24 hours",
            "Saturday: Open 24 hours",
            "Sunday: Open 24 hours"
         ]
      },
      "rating" : 4.7
   },
   "status" : "OK"
}

```
## Tutorial 1+2

https://raghadestanbouli.github.io/GoogleAPI/Gmaps/tutorial.html

## Tutorial 3

https://raghadestanbouli.github.io/GoogleAPI/Gmaps/tutorial3a.html
https://raghadestanbouli.github.io/GoogleAPI/Gmaps/tutorial3b.html
https://raghadestanbouli.github.io/GoogleAPI/Gmaps/tutorial3c.html

