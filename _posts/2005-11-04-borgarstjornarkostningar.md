---
layout: post
title: Borgarstjórnarkostningar
date: 2005-11-04 14:01
author: sporri
comments: true

---
Þetta er ekki mitt mál lengur, hvorki Gísli Marteinn né Vilhjálmur eru í framboði í den Haag, hvað þá Kópavogi. En skoðanakönnun á visir.is sýnir óvæntar niðurstöður.

Fylgi án endurtekinna iptala:

<a href="http://stod2.visir.is/lisalib/objects/surveys/chart.aspx?questionid=51&amp;width=600&amp;fontsize=12&amp;ExcludeDuplicatedIP=true"><img src="http://stod2.visir.is/lisalib/objects/surveys/chart.aspx?questionid=51&amp;width=200&amp;fontsize=8&amp;ExcludeDuplicatedIP=true" alt="Einkvæmar IP tölur" border="0"></a>

Fylgi með endurteknum iptölum:

<a href="http://stod2.visir.is/lisalib/objects/surveys/chart.aspx?questionid=51&amp;width=600&amp;fontsize=12&amp;ExcludeDuplicatedIP=false"><img src="http://stod2.visir.is/lisalib/objects/surveys/chart.aspx?questionid=51&amp;width=200&amp;fontsize=8&amp;ExcludeDuplicatedIP=false" alt="Allar IP Tölur" border="0"></a>

Ég er ekki tölfræðisnillingur, en ég sé ekki að þessi munur skýrist einungis af þeim sem tvísmella á senda eða eru bak við NAT/PAT. Annar hvor aðilinn hlýtur að sitja heima og margkjósa. 

-
Tækniskýringin, þessar tvær myndir eru fengnar frá stod2.visir.is og eru birtar beint upp úr gagnagrunni með fyrirspurn sem sést sem slóðin á myndirnar. 
Ef þú smellir á mynd og skoðar slóðina þá sést að hún endar á ExcludeDuplicatedIP=true, breyttu true í false (í address línunni, og smelltu svo á enter), þá er myndin teiknuð upp aftur eftir nýrri fyrirspurn sem telur allar iptölur sem svöruðu en sleppir ekki þeim sem eru endurteknar.
