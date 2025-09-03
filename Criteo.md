**4.Criteo-**

**List Of Tables Under Criteo: -**

| Schema Name | Table Name | SLA | Load_Time | Load_Frequency | frequecy_of_ingestion_with_time | Ingestion_flow |
| --- | --- | --- | --- | --- | --- | --- |
| prd_mdf_fnd | criteo_campaign_dly | 11.30PM CST | 12.30AM CST | Daily | 1, 12.30AM CST | criteo→ sftp server → sb → s3poller → /user/SVMDEDMP/hive/criteo/criteo_campaign_dly/criteo_campaign_dly_land |
|  | criteo_category_dly | 11AM CST | 12.30AM CST | Daily | 1, 12.30AM CST | criteo→ sftp server → sb → s3poller → /user/SVMDEDMP/hive/criteo/criteo_category_dly/criteo_category_dly_land |
|  | criteo_category_advertiser_dly | 11AM CST | 12.30AM CST | Daily | 1, 12.30AM CST | criteo→ sftp server → sb → s3poller → /user/SVMDEDMP/hive/criteo/criteo_category_advertiser_dly/criteo_category_advertiser_dly_land |
|  | criteo_category_keyword_dly | 10.30PM CST | 12.30AM CST | Daily | 1, 12.30AM CST | criteo→ sftp server → sb → s3poller → /user/SVMDEDMP/hive/criteo/criteo_category_keyword_dly/criteo_category_keyword_dly_land |
|  | criteo_monthly | NA | 12.30AM CST | Daily | 1, 12.30AM CST |  |
|  | criteo_floor_price | NA | NA | NA | NA | NA |
|  | criteo_capout_daily | 2:00 PM CST | At 12:40 CST | Daily | 1, At 12:40 CST | criteo->file express→ common ingestion ->/user/SVMDEDMP/hive/criteo/criteo_capout_dly/criteo_capout_dly_land |
|  | criteo_dsp_category_advertiser_dly | At 11:00 AM | At 05:30 UTC | Daily | 1, At 05:30 UTC | criteo->file express→ common ingestion →/user/SVMDEDMP/hive/criteo_dsp/criteo_dsp_keyword_advertiser_dly/daily_landing |
|  | criteo_dsp_category_keyword_dly | At 11:00 AM | At 05:30 UTC | Daily | 1, At 05:30 UTC | criteo->file express→ common ingestion →/user/SVMDEDMP/hive/criteo_dsp/criteo_dsp_keyword_advertiser_dly/daily_landing |