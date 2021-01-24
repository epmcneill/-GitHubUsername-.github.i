Simply adding the directions request URL inside of an iframe does not work!

I did find documentation that outlines how the route returned can be [visualized](https://developers.google.com/maps/documentation/javascript/directions), however I don't think this particualr solution was the goal of the task.

As of **Jan 24th**, I have not found a solution yet after messing around, but will keep looking.

**URL**

https://maps.googleapis.com/maps/api/directions/json?origin=St+Thomas+ON&destination=London+ON&avoid=highways&key=AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

**RESPONSE**

{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJRT8C5j9eLogR1jyNvv24Nhc",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJC5uNqA7yLogRlWsFmmnXxyg",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 42.9849367,
               "lng" : -81.179974
            },
            "southwest" : {
               "lat" : 42.7782052,
               "lng" : -81.24527309999999
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "27.3 km",
                  "value" : 27308
               },
               "duration" : {
                  "text" : "32 mins",
                  "value" : 1897
               },
               "end_address" : "London, ON, Canada",
               "end_location" : {
                  "lat" : 42.98491629999999,
                  "lng" : -81.24527309999999
               },
               "start_address" : "St Thomas, ON, Canada",
               "start_location" : {
                  "lat" : 42.7782052,
                  "lng" : -81.1828714
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1640
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 216
                     },
                     "end_location" : {
                        "lat" : 42.7929493,
                        "lng" : -81.1825638
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eBalaclava St\u003c/b\u003e toward \u003cb\u003eTalbot St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ybbdG|_onNcCSq@Ac@?qGEwE?mCAsDCc@?mAAU@g@Cy@?c@?mCAoCAgA?yGE[?eAAkB?cA?mHCsDCkB?oCC"
                     },
                     "start_location" : {
                        "lat" : 42.7782052,
                        "lng" : -81.1828714
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 223
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 42.793199,
                        "lng" : -81.18003999999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eS Edgeware Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}~ddG~}nnNQEIEEEEGGKCKCKAU@_C@wB@]@mC"
                     },
                     "start_location" : {
                        "lat" : 42.7929493,
                        "lng" : -81.1825638
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2208
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 130
                     },
                     "end_location" : {
                        "lat" : 42.813056,
                        "lng" : -81.18011
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDalewood Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o`edGfnnnNc@?kBCgA?sDCaBAwEDeB@E?y@?q@?gAGS?[AY?I?c@@yB@eBCOA{A@kB?kB?aE?y@?_H@qI@mFDkBBgJHkB@mCByCAc@?wE?aAA"
                     },
                     "start_location" : {
                        "lat" : 42.793199,
                        "lng" : -81.18003999999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.5 km",
                        "value" : 2463
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 129
                     },
                     "end_location" : {
                        "lat" : 42.8124742,
                        "lng" : -81.21000149999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRon McNeil Line\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 52\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s|hdGtnnnNDPf@rB\\xALj@j@dCXzAJl@BLV~BHn@Df@H|C@lC?Z?TSxOGfKM~Q?HSx[KzRYvc@EpHClG"
                     },
                     "start_location" : {
                        "lat" : 42.813056,
                        "lng" : -81.18011
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "12.8 km",
                        "value" : 12783
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 616
                     },
                     "end_location" : {
                        "lat" : 42.91972579999999,
                        "lng" : -81.2102469
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 25\u003c/b\u003e (signs for \u003cb\u003eLondon\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWellington Road\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Road 25\u003c/b\u003e)\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Wellington Rd\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}xhdGnitnN{F?cR?sDAwE?c@?iB?gA?gA?wE?kB?aM?uBAgC?mGAkKC_QEgJCsMCaA?{DAkEAuOGgJCqDAcICsDAoFAg@Aq@Ac@?iOMs@@E?a@B]BYDoKbBiLbBeKzAmFv@aEn@{G`AiBT}@B_A?u@EaAMy@SaA]o@]c@Wi@a@[S]]WWMOOSIKIKOSS]QYO[MUISQa@Qg@Y}@Mc@Ke@GYEYESEUCWE_@EYAOAOCc@Eg@EaAEkAKqCMqCKqCOcEAGAg@GsAKyBCc@Ek@AEAQEUEYEWCSEWGUESEUQe@e@wAa@_Ac@w@k@w@]a@o@m@i@e@q@c@s@_@o@Um@Oo@Kc@Gw@EwA@Y@g@FmAPmBVuCb@mDh@}HlAaJrAmInAeEn@qDh@_IhA{Cb@c@FeALOBcDRc@D_@BC?sAHyAFoBRYDk@HoXdEoDj@sEt@c@HyGfAc@HqBZI@_BXaC`@q@LkDl@aHfAkBZ_BTqBViBVyBZqANwFp@cHr@gd@tE_Gn@yAPSBc@FA?}Hz@yEj@wAXe@FSDm@JYFODk@NGBu@TGBmAf@i@Pc@RIDi@TWLc@PKFe@PIBOFm@Vg@Rc@@{@X_C`A_Br@"
                     },
                     "start_location" : {
                        "lat" : 42.8124742,
                        "lng" : -81.21000149999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.0 km",
                        "value" : 7991
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 785
                     },
                     "end_location" : {
                        "lat" : 42.98491629999999,
                        "lng" : -81.24527309999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eWellington Rd S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "iw}dG`ktnNmAj@o@Z[PmAt@cBhAgBtAu@t@WTUVC@k@j@WXWVEDWZe@j@k@r@_AlACBkAjBYb@eAbBCDOVmApBi@v@k@~@U^[f@ORQVc@f@kArAA?Ul@IJQLSP_BrAYR{@j@UNCB[NYLSJg@Lg@Xc@NOFaA^C@y@^i@XSJKCIDkAr@QJaA|@MLe@b@_@Zo@p@eBhBk@l@g@f@aBlAIDqA|@wBjAEBcA^IBWJg@Jc@Ji@Lu@Ny@PYD]DUDaANsAPsAPkC`@aDb@eBToC`@}Dn@eANsAN[Dc@FiARa@FQBgDl@WHo@Ru@XkAd@i@RoAn@YNMFm@XQTg@Pg@R}Ar@QHOFMDKDKBMFI@GBMBMDe@HE@o@JmAPiBVMB{Er@MBuDf@YAYByAP}@NI?e@JUDyARkAN}@Nc@FyATy@LQD_@Fs@J_@DaBVg@Hc@FoAN_BNkAJyDf@gAPYDuDh@cBZ_BZA@kB^q@Jw@Pa@Fy@L_BTe@H_@He@JQFIJMB_ANq@JmCb@m@FcC^kAPaBVmDf@kANYDYJIDIHMLKLIP[p@{AlDu@bBi@nAk@lAq@xAEHILGJEDEDIJg@`@}@l@oA~@eCfBcAt@a@XsAdAeAx@gBpAw@n@YVWTa@X]Vo@d@[TUPEBOJUNUPQJOJUNOAK@ID}@^yBz@uBx@uBz@wBz@SHyAl@_C~@mBv@uBx@QF{@`@a@PoB|@WJaA`@a@NQHgAb@a@NOFMFaA^wChAk@TyAj@gBp@BL"
                     },
                     "start_location" : {
                        "lat" : 42.91972579999999,
                        "lng" : -81.2102469
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "ybbdG|_onNcCSq@AuHE}PEcB?aBCiKCyb@OoCCQEOKMSGW?uCBuC@mCc@?sDCuGE}HF_A?q@?gAGo@Ac@?}CBuBEuN@yI@_QFmURwMCxAjGj@dCXzANz@`@nDDf@H|C@hDSnPi@j{@o@riAio@A{ZAaj@KuhAYoWIuAAiOMs@@g@Bw@HyXfEsRrC}MpBiBT}@B_A?u@EaAMy@SaA]o@]mAy@y@q@e@g@s@_AcAiB[u@k@eBg@}BUaBM}AiAwXYyGOyAU}AMi@W{@gAwCoAoBmAoA{AiAcBu@}A[{AMqBByJtA{c@zGsYfEiBTsDV{CRyAFoBReAN_^pFwF~@yLnB_MvBmKbBqEl@cFr@iI`Akm@hGyI`AwJfAyEj@wAXy@LgAR{@TsCdAoFzBoBv@c@@{@X_FtB}BfAiBfAcBhAgBtAmAjA}A~A{AdBkB`CoAnBsBdDyDhGk@z@u@~@mArA_@x@_DfCqAz@_@Rm@Xg@Lg@Xs@VeA`@cBx@SJKCuAx@QJaA|@s@p@oAlAqCvCg@f@aBlA{AbA}BnAmAb@_AV}Dz@oC`@uMhBuFv@cG~@oBTmBZs@J_Ev@eBl@uBx@eD`BQTg@PeCfA{@\\c@LiAVmFv@mLbBYAYBwC`@_Dd@gG|@mJvAoD^kAJyDf@aBVyGdA_GhAsF|@eARw@RIJMBqBZkK|AuJtAc@PWVU^wB~E}DzI]h@OPeBnA{HvFyH`Gq@l@_Ap@gBpAmAx@e@Z[?wHzCqUhJeF|B}D~AgO|FBL"
         },
         "summary" : "Wellington Rd",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
