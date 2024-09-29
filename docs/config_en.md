| Configuration Item      | Default Value                                                                                                                                                                                                   | Description                                                                                                                                |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| open_update             | True                                                                                                                                                                                                            | Enable updates, if disabled then only the result page service is run                                                                       |
| open_use_old_result     | True                                                                                                                                                                                                            | Enable the use of historical update results (including the interface for template and result files) and merge them into the current update |
| open_driver             | True                                                                                                                                                                                                            | Enable browser execution, If there are no updates, this mode can be enabled, which consumes more performance                               |
| open_proxy              | False                                                                                                                                                                                                           | Enable proxy, automatically obtains free available proxies, If there are no updates, this mode can be enabled                              |
| source_file             | config/demo.txt                                                                                                                                                                                                 | Template file path                                                                                                                         |
| final_file              | output/result.txt                                                                                                                                                                                               | Generated result file path                                                                                                                 |
| open_online_search      | False                                                                                                                                                                                                           | Enable online search source feature                                                                                                        |
| online_search_page_num  | 3                                                                                                                                                                                                               | Page retrieval quantity for online search channels                                                                                         |
| urls_limit              | 15                                                                                                                                                                                                              | Number of interfaces per channel                                                                                                           |
| open_keep_all           | False                                                                                                                                                                                                           | Retain all search results, retain results with non-template channel names, recommended to be turned on when manually maintaining           |
| open_sort               | True                                                                                                                                                                                                            | Enable the sorting function (response speed, date, resolution)                                                                             |
| open_ffmpeg             | True                                                                                                                                                                                                            | Enable speed testing using FFmpeg to obtain more accurate speed and resolution information. Manual installation is required in advance.    |
| open_m3u_result         | True                                                                                                                                                                                                            | Enable the conversion to generate m3u file type result links, supporting the display of channel icons                                      |
| response_time_weight    | 0.5                                                                                                                                                                                                             | Response time weight value (the sum of all weight values should be 1)                                                                      |
| resolution_weight       | 0.5                                                                                                                                                                                                             | Resolution weight value (the sum of all weight values should be 1)                                                                         |
| recent_days             | 30                                                                                                                                                                                                              | Retrieve interfaces updated within a recent time range (in days), reducing appropriately can avoid matching issues                         |
| ipv_type                | ipv4                                                                                                                                                                                                            | The type of interface in the generated result, optional values: ipv4, ipv6, all                                                            |
| domain_blacklist        | epg.pw                                                                                                                                                                                                          | Interface domain blacklist, used to filter out interfaces with low-quality, ad-inclusive domains                                           |
| url_keywords_blacklist  |                                                                                                                                                                                                                 | Interface keyword blacklist, used to filter out interfaces containing specific characters                                                  |
| open_subscribe          | False                                                                                                                                                                                                           | Enable subscription source feature                                                                                                         |
| subscribe_urls          | https://m3u.ibert.me/txt/fmml_dv6.txt,<br>https://m3u.ibert.me/txt/o_cn.txt,<br>https://m3u.ibert.me/txt/j_iptv.txt,<br>https://github.moeyy.xyz/https://raw.githubusercontent.com/PizazzGY/TVBox/main/live.txt | Subscription source list                                                                                                                   |
| open_multicast          | True                                                                                                                                                                                                            | Enable multicast source function                                                                                                           |
| open_multicast_tonkiang | True                                                                                                                                                                                                            | Enable Tonkiang multicast source work mode                                                                                                 |
| open_multicast_fofa     | True                                                                                                                                                                                                            | Enable FOFA multicast source work mode                                                                                                     |
| multicast_region_list   | all                                                                                                                                                                                                             | Multicast source region list, [more regions](../updates/multicast/multicast_map.json, all means all regions)                               |
| multicast_page_num      | 3                                                                                                                                                                                                               | Number of pages to retrieve for multicast regions                                                                                          |
| open_hotel              | True                                                                                                                                                                                                            | Enable hotel source feature                                                                                                                |
| open_hotel_tonkiang     | False                                                                                                                                                                                                           | Enable Tonkiang hotel source work mode                                                                                                     |
| open_hotel_fofa         | True                                                                                                                                                                                                            | Enable FOFA、ZoomEye hotel source work mode                                                                                                |
| hotel_region_list       | all                                                                                                                                                                                                             | List of hotel source regions, [more regions](../updates/fofa/fofa_map.py), 'all' indicates all regions                                     |
| hotel_page_num          | 3                                                                                                                                                                                                               | Number of pages to retrieve for hotel regions                                                                                              |