# fed-unis-perf-eval

The aim of this study is to evaluate the accessibility and performance of the official websites of the forty-nine (49) accredited Federal Universities in Nigeria by using the Google Lighthouse web auditing tool.

The auditing is performed using [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) and the [lighthouse-batch](https://github.com/mikestead/lighthouse-batch) library. Kindly note the following:

- The generated report for each university is available in JSON, HTML, and CSV formats.
- The generated report for each university can be found in the `/lighthouse report/<university name>` directory.
- The generated summary report for each university can be found in the [`summary.json`](./summary.json) file (view the RAW format [here](https://raw.githubusercontent.com/BolajiAyodeji/fed-unis-perf-eval/main/summary.json)).
- The concluding report data for the research can be found in the [`summary.csv`](./summary.csv) file.

## Lighthouse report

The table below lists out the universities evaluated and a link to view the generated HTML report which includes the performance scores, errors found, reference links to learn more about each error, and Lighthouse recommended improvements.

| **University name**                               | **Link to full report**                                                                                                                       |
|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Abubakar Tafawa Balewa University                 | [click_here](https://fed-unis-perf-eval.netlify.app/Abubakar%20Tafawa%20Balewa%20University/atbu_edu_ng_.report.html)                         |
| Ahmadu Bello University                           | [click_here](https://fed-unis-perf-eval.netlify.app/Ahmadu%20Bello%20University/abu_edu_ng_.report.html)                                      |
| Air Force Institute of Technology                 | [click_here](https://fed-unis-perf-eval.netlify.app/Air%20Force%20Institute%20of%20Technology/afit_edu_.report.html)                          |
| Bayero University Kano                            | [click_here](https://fed-unis-perf-eval.netlify.app/Bayero%20University%20Kano/buk_edu_ng_.report.html)                                       |
| Federal University Birnin Kebbi                   | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Birnin%20Kebbi/fubk_edu_ng_.report.html)                           |
| Federal University Dustin-Ma                      | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Dustin-Ma/fudutsinma_edu_ng_.report.html)                          |
| Federal University Dutse                          | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Dutse/fud_edu_ng_.report.html)                                     |
| Federal University Gashua                         | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Gashua/fugashua_edu_ng_.report.html)                               |
| Federal University Gusau                          | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Gusau/fugusau_edu_ng_.report.html)                                 |
| Federal University Kashere                        | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Kashere/fukashere_edu_ng_.report.html)                             |
| Federal University Lafia                          | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Lafia/fulafia_edu_ng_.report.html)                                 |
| Federal University Lokoja                         | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Lokoja/fulokoja_edu_ng_.report.html)                               |
| Federal University Ndifu-Alike                    | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Ndifu-Alike/funai_edu_ng_.report.html)                             |
| Federal University Otuoke                         | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Otuoke/fuotuoke_edu_ng_.report.html)                               |
| Federal University Oye-Ekiti                      | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Oye-Ekiti/fuoye_edu_ng_.report.html)                               |
| Federal University Wukari                         | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20Wukari/fuwukari_edu_ng_.report.html)                               |
| Federal University of Agriculture Abeokuta        | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Agriculture%20Abeokuta/unaab_edu_ng_.report.html)             |
| Federal University of Agriculture Makurdi         | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Agriculture%20Makurdi/uam_edu_ng_.report.html)                |
| Federal University of Agriculture Zuru            | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Agriculture%20Zuru/fuaz_edu_ng_.report.html)                  |
| Federal University of Health Technology Otukpo    | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Health%20Technology%20Otukpo/fuhso_ng_.report.html)           |
| Federal University of Petroleum Resources Effurun | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Petroleum%20Resources%20Effurun/fupreonline_com_.report.html) |
| Federal University of Technology Akure            | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Technology%20Akure/futa_edu_ng_.report.html)                  |
| Federal University of Technology Minna            | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Technology%20Minna/futminna_edu_ng_.report.html)              |
| Federal University of Technology Owerri           | [click_here](https://fed-unis-perf-eval.netlify.app/Federal%20University%20of%20Technology%20Owerri/futo_edu_ng_.report.html)                 |
| Michael Okpara University of Agricultural Umudike | [click_here](https://fed-unis-perf-eval.netlify.app/Michael%20Okpara%20University%20of%20Agricultural%20Umudike/mouau_edu_ng_.report.html)    |
| Modibbo Adama University of Technology            | [click_here](https://fed-unis-perf-eval.netlify.app/Modibbo%20Adama%20University%20of%20Technology/mautech_edu_ng_new_.report.html)           |
| National Open University of Nigeria               | [click_here](https://fed-unis-perf-eval.netlify.app/National%20Open%20University%20of%20Nigeria/nou_edu_ng_.report.html)                      |
| Nigeria Police Academy Wudil                      | [click_here](https://fed-unis-perf-eval.netlify.app/Nigeria%20Police%20Academy%20Wudil/polac_edu_ng_.report.html)                             |
| Nigerian Army University Biu                      | [click_here](https://fed-unis-perf-eval.netlify.app/Nigerian%20Army%20University%20Biu/naub_edu_ng_.report.html)                              |
| Nigerian Defence Academy                          | [click_here](https://fed-unis-perf-eval.netlify.app/Nigerian%20Defence%20Academy/nda_edu_ng_.report.html)                                     |
| Nigerian Maritime University                      | [click_here](https://fed-unis-perf-eval.netlify.app/Nigerian%20Maritime%20University/nmu_edu_ng_.report.html)                                 |
| Nnamdi Azikiwe University                         | [click_here](https://fed-unis-perf-eval.netlify.app/Nnamdi%20Azikiwe%20University/unizik_edu_ng_.report.html)                                 |
| Obafemi Awolowo University                        | [click_here](https://fed-unis-perf-eval.netlify.app/Obafemi%20Awolowo%20University/oauife_edu_ng_.report.html)                                |
| University of Abuja                               | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Abuja/uniabuja_edu_ng_.report.html)                                     |
| University of Benin                               | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Benin/uniben_edu_ng_.report.html)                                       |
| University of Calabar                             | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Calabar/unical_com_.report.html)                                        |
| University of Ibadan                              | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Ibadan/ui_edu_ng_.report.html)                                          |
| University of Ilorin                              | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Ilorin/www_unilorin_edu_ng_.report.html)                                |
| University of Jos                                 | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Jos/unijos_edu_ng_.report.html)                                         |
| University of Lagos                               | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Lagos/unilag_edu_ng_.report.html)                                       |
| University of Maiduguri                           | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Maiduguri/unimaid_edu_ng_.report.html)                                  |
| University of Nigeria Nsukka                      | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Nigeria%20Nsukka/unn_edu_ng_.report.html)                               |
| University of Port-Harcourt                       | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Port-Harcourt/uniport_edu_ng_.report.html)                              |
| University of Uyo                                 | [click_here](https://fed-unis-perf-eval.netlify.app/University%20of%20Uyo/uniuyo_edu_ng_.report.html)                                         |
| Usman Danfodiyo University                        | [click_here](https://fed-unis-perf-eval.netlify.app/Usman%20Danfodiyo%20University/udusok_edu_ng_.report.html)                                |
