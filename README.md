# Tilastokirja - updates

Tilastokirja on kunnille suunnattu tietopaketti. Pääosa tiedoista on haettu Tilastokeskuksen rajapinnoilta. Tilastokirjaa kehitetään eteenpäin toiveiden mukaan.
Kirjan voi ajaa [quart](https://quarto.org/) ohjelmistolla. Pääosa koodista on markdown ja r-koodia.

## 8.5.2023 - Added greenhouse gases
#Tilastokeskus: 121z -- Kasvihuonekaasupäästöt alueittain, päästökaupan ulkopuoliset tiedot, 2011-2020
CHARTS - \_chart_ilmasto_paastot.qmd
TABLES - \_tbl_ilmasto_paastot.qmd

## 3.5.2023 - Added population pyramid

CHARTS - \_chart_vaestopyramidi.qmd

## 27.4.2023 - Added population 5 classes

#StatFin / Väestörakenne / 11ra -- Tunnuslukuja väestöstä alueittain, 1990-2022 stat_url_11ra: "https://pxdata.stat.fi:443/PxWeb/api/v1/fi/StatFin/vaerak/statfin_vaerak_pxt_11ra.px"

#StatFin / Väestörakenne / 11re -- Väestö iän (1-v.) ja sukupuolen mukaan alueittain, 1972-2022 stat_url_11re: "https://pxweb2.stat.fi:443/PxWeb/api/v1/fi/StatFin/vaerak/statfin_vaerak_pxt_11re.px"

TABLES - \_tbl_vaesto_1v.qmd - \_tbl_vaesto_ikaryhmat_5lk_pro.qmd - \_tbl_vaesto_ikaryhmat_5lk.qmd - \_tbl_vaesto_osa_alueet.qmd - \_tbl_vaesto.qmd

CHARTS - \_chart_vaesto_ikaryhmat_5lk.qmd - \_chart_vaesto.qmd

PARAMS - color update (more colors added)
