---
layout: page-with-side-nav
title: Documentatie StUF-BAG-GBA
folder_files:
  - title: 1. Proceshandreiking gba-bag versie 1.01
    path: documenten/1._Proceshandreiking_gba-bag_versie_1.01.pdf
    group: 310
    versie: 1.01
    status: 
    omschrijving: 
  - title: 2. Koppelvlakbeschrijving BAG-GBA obv StUF 3 01 (v 0 5) 
    path: documenten/2._Koppelvlakbeschrijving_BAG-GBA_obv_StUF_3_01_(v_0_5).pdf
    group: 310
    versie: 0.5
    status: 
    omschrijving: 
  - title: 3. src baggba 2103
    path: documenten/3._src_baggba_2103.zip
    group: 310
    versie: 2.10
    status: 
    omschrijving: 
  - title: 5. Wijzigingsverzoek RFC v1
    path: documenten/5._Wijzigingsverzoek_RFC_v1.pdf
    group: 310
    versie: 1.0
    status: 
    omschrijving: 
  - title: BAG GBA Koppelvlak beschrijving
    path: documenten/BAG_GBA_Koppelvlak_beschrijving.pdf
    group: 204
    versie: 1.3
    status: Definitief
    omschrijving: 
  - title: BAG GBA Koppelvlak beschrijving (met renvooi)
    path: documenten/BAG_GBA_Koppelvlak_beschrijving_(met_renvooi).pdf
    group: 204
    versie: 1.3
    status: Definitief
    omschrijving: 
  - title: BAG GBA StUF regiegroep begeleidend schrijven
    path: documenten/BAG_GBA_StUF_regiegroep_begeleidend_schrijven.pdf
    group: 204
    versie: 1.2
    status: 
    omschrijving: 
  - title: BAG GBA Toepassing per leverancier
    path: documenten/BAG_GBA_Toepassing_per_leverancier.pdf
    group: 204
    versie: 1.3
    status: 
    omschrijving: 
  - title: Inventarisatiegebeurtenissenbagvsgba v1
    path: documenten/Inventarisatiegebeurtenissenbagvsgba_v1.2.xls.zip
    group: 204
    versie: 
    status: 
    omschrijving: 
  - title: Koppeling BAGGBA Voorbeeldberichten v1.2 
    path: documenten/Koppeling_BAGGBA_Voorbeeldberichten_v1.2.zip
    group: 204
    versie: 1.2
    status: 
    omschrijving: 
---

# Documentatie

## BAG-GBA 3.10 (In ontwikkeling)

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 310 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## BAG-GBA 2.04

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 204 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
