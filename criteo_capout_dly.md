### About This Dataset

| Asset name: | prd_mdf_fnd.criteo_capout_dly |
| --- | --- |
| Description: | This daily dataset is used to highlight campaign records where capout budget was reached at a specific time of a day |
| Business Use Cases: | In cases of campaign where the ad spend was restricted due to setup of a capout amount, this visibility would allow account managers to have data driven discussion with advertisers around campaign budget limits and the opportunities to increase spend for higher sales. |
| Primary Users: | P&I(Performance and Insights), FOH(Front of House). |
| Security Classification | Internal |
| Source(s) of Data: | Criteo Capout API → MDFDaryk Childs - d.childs@criteo.comKelvon Hayes - ke.hayes@criteo.comConnor Bell - c.bell@criteo.com |
| Grain of Data: | retailer_name, account_id, account_name, account_external_id, campaign_id, campaign_name, campaign_external_id, line_item_id, line_item_name, line_item_external_id, percent_active, missed_ad_spend, working_media, total_demand, alert_hour, load_d |
| Metadata/ Getting Started: | https://dataportal.prod.target.com/assets/5971680/?view=%22fields%22 |
| Update Frequency: | See "Scheduling" tab on this page |
| Update Method | BR3: Shepherd jobs |
| SLA | 2:00 PM CST |
| Shepherd Workflow | https://shepherd.prod.target.com/workflow/9565173 |
| GIT Link: | DIP → https://git.target.com/data-engineering-mktg-data-foundation/mdf-api-kelsa-dipDPP → https://git.target.com/data-engineering-mktg-data-foundation/criteo-capout-pipeline |
| Test Coverage: | https://desonar.prod.target.com/dashboard?id=data-engineering-mktg-data-foundation.criteo-capout-pipeline |
| Pipeline Monitor: | https://visualize.prod.target.com/d/QSyol_8Ik/criteo-capout-daily-dpp-prod?orgId=1 |
| DataPortal Links: | https://dataportal.prod.target.com/assets/5971680/?view=%22fields%22 |
| Vela Link: | https://vela.prod.target.com/data-engineering-mktg-data-foundation/criteo-capout-pipeline |
| Support: | Service Now Incident for data defects/issues:Assign Group: DataSciences-DE-MarketingDataFoundation-Supportemail - DataSciences-DE-MDF-TM@Target.com |