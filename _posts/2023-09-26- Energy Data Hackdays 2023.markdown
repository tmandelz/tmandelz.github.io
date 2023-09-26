---
layout: post
title:  "Are we still sss towards the ozone hole?"
subtitle: "A self learning visualisation approach to the silent ozone hole progression."
date:   2023-09-26 17:35:43 +0200
categories: visualisations ozone  
---

<div style="text-align: center">

<a href="https://ozonewatch.gsfc.nasa.gov/ozone_maps/images/Y2021/M09/OZONE_D2021-09-26_G%5E716X716.IOMPS_PNPP_V21_MGEOS5FP_LSH.PNG">
 <figure>
  <img src="/images/ozone/ozonemapprojection.png" align="center" alt="Ozone Map Projection" style="width:100%">
  <figcaption>Figure 1 - (Ozonewatch, 2021a)</figcaption>
</figure> 

</a>
</div>



# My Inspiration and goals
As I listened to an episode of the Startalk podcast (deGrasse Tyson, 2021) I was reminded of the ozone depletion which was a threat in my infant and teen years. Since then, I have not heard of any developments in recent years. So, I decided to check out this topic and get some experience in data visualisation as well. My idea was to create an interactive plot for the timeline of the ozone hole depletion size. In this plot I marked the important events in the timeline and added a description to them. 
My aim is that you as a reader know about the ozone hole progression and if we are silently falling into a pitfall or if there is a solution in sight. You may also learn, along with me, the basics of a building an interactive visualisation.


<div style="margin-top: 100px;">
<h1> Sources</h1>

<div class="csl-bib-body" style="line-height: 2; margin-left: 2em; text-indent:-2em;">
  <div class="csl-entry">deGrasse Tyson, N. (2021, September 14). <i>Cosmic Queries in the O-zone: Saving the World with Susan Solomon &amp; Stephen Andersen - StarTalk Radio</i> (No. 36). <a href="https://www.startalkradio.net/show/cosmic-queries-in-the-o-zone-saving-the-world-with-susan-solomon-stephen-andersen/">https://www.startalkradio.net/show/cosmic-queries-in-the-o-zone-saving-the-world-with-susan-solomon-stephen-andersen/</a></div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=podcast&amp;rft.title=Cosmic%20Queries%20in%20the%20O-zone%3A%20Saving%20the%20World%20with%20Susan%20Solomon%20%26%20Stephen%20Andersen%20-%20StarTalk%20Radio&amp;rft.rights=Public%20domain%2C%20via%20Wikimedia%20Commons&amp;rft.description=How%20did%20we%20save%20the%20ozone%20layer%3F%20Neil%20deGrasse%20Tyson%20and%20Chuck%20Nice%20break%20down%20the%20campaign%20to%20save%20the%20ozone%20layer%20with%20Susan%20Solomon%20and%20Stephen%20Andersen.&amp;rft.identifier=https%3A%2F%2Fwww.startalkradio.net%2Fshow%2Fcosmic-queries-in-the-o-zone-saving-the-world-with-susan-solomon-stephen-andersen%2F&amp;rft.aufirst=Neil&amp;rft.aulast=deGrasse%20Tyson&amp;rft.au=Neil%20deGrasse%20Tyson&amp;rft.language=en-US"></span>
  <div class="csl-entry">Manjiri Mulye. (2017, January 30). Kigali Agreement: Simplified. <i>ClearIAS</i>. <a href="https://www.clearias.com/kigali-agreement/">https://www.clearias.com/kigali-agreement/</a></div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=blogPost&amp;rft.title=Kigali%20Agreement%3A%20Simplified&amp;rft.description=Paris%20Agreement%20was%20followed%20by%20another%20major%20global%20agreement%20-%20Kigali%20Agreement.%20In%20this%20post%2C%20we%20explain%20the%20importance%20of%20Kigali%20agreement.&amp;rft.identifier=https%3A%2F%2Fwww.clearias.com%2Fkigali-agreement%2F&amp;rft.au=undefined&amp;rft.date=2017-01-30&amp;rft.language=en-US"></span>
  <div class="csl-entry">Ozonewatch. (2021a). <i>Ozone Map Projection 26.09.2021</i>. <a href="https://ozonewatch.gsfc.nasa.gov/ozone_maps/images/Y2021/M09/OZONE_D2021-09-26_G%5E716X716.IOMPS_PNPP_V21_MGEOS5FP_LSH.PNG">https://ozonewatch.gsfc.nasa.gov/ozone_maps/images/Y2021/M09/OZONE_D2021-09-26_G%5E716X716.IOMPS_PNPP_V21_MGEOS5FP_LSH.PNG</a></div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=artwork&amp;rft.title=Ozone%20Map%20Projection%2026.09.2021&amp;rft.identifier=https%3A%2F%2Fozonewatch.gsfc.nasa.gov%2Fozone_maps%2Fimages%2FY2021%2FM09%2FOZONE_D2021-09-26_G%255E716X716.IOMPS_PNPP_V21_MGEOS5FP_LSH.PNG&amp;rft.aulast=Ozonewatch&amp;rft.au=Ozonewatch&amp;rft.date=2021-09-26"></span>
  <div class="csl-entry">Ozonewatch, N. (2018, October 18). <i>Nasa Ozone Watch: Ozone hole history facts</i>. <a href="https://ozonewatch.gsfc.nasa.gov/facts/history_SH.html">https://ozonewatch.gsfc.nasa.gov/facts/history_SH.html</a></div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=Nasa%20Ozone%20Watch%3A%20Ozone%20hole%20history%20facts&amp;rft.identifier=https%3A%2F%2Fozonewatch.gsfc.nasa.gov%2Ffacts%2Fhistory_SH.html&amp;rft.aufirst=NASA&amp;rft.aulast=Ozonewatch&amp;rft.au=NASA%20Ozonewatch&amp;rft.date=2018-10-18"></span>
  <div class="csl-entry">Ozonewatch, N. (2021b, September 26). <i>NASA Ozone Watch: Latest status of ozone</i>. Latest Status of Ozone. <a href="https://ozonewatch.gsfc.nasa.gov/">https://ozonewatch.gsfc.nasa.gov/</a></div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=webpage&amp;rft.title=NASA%20Ozone%20Watch%3A%20Latest%20status%20of%20ozone&amp;rft.identifier=https%3A%2F%2Fozonewatch.gsfc.nasa.gov%2F&amp;rft.aufirst=NASA&amp;rft.aulast=Ozonewatch&amp;rft.au=NASA%20Ozonewatch&amp;rft.date=2021-09-26&amp;rft.language=en"></span>
  <div class="csl-entry">R. Nash, E. (2021, December 14). <i>Ozone Depletion Article—Data Questions</i> [Personal communication].</div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Adc&amp;rft.type=email&amp;rft.description=Thank%20you%20for%20your%20interest%20in%20NASA's%20Ozone%20Watch.%20There%20were%20no%20satellites%20available%20during%20that%20period%20that%20measured%20global%20total%20column%20ozone.%20The%20last%20TOMS%20instrument%20was%20onboard%20the%20Meteor-3%20satellite%20that%20ended%20in%201994.%20The%20Earth%20Probe%20TOMS%20satellite%20wasn't%20launched%20until%201996.%20Other%20missing%20data%20here%20and%20there%20throughout%20the%20data%20record%20are%20due%20to%20technical%20issues%20with%20either%20the%20instrument%20or%20the%20satellite.&amp;rft.aufirst=Eric&amp;rft.aulast=R.%20Nash&amp;rft.au=Eric%20R.%20Nash&amp;rft.date=2021-12-14&amp;rft.language=en"></span>
</div>


</div>