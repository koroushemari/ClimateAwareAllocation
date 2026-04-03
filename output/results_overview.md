# Allocation Results

Current scope: global NGFS aggregation, 2027 snapshot, rescaled firm-level eta, 5,000-firm portfolio, and a nonlinear loss engine with regime-switch amplification.

## Scenario summary

| Scenario | Mean PD | Capital-weighted PD | Effective obligors | Top 20 capital share | Top allocated sector | Top allocated region |
|---|---:|---:|---:|---:|---|---|
| DAPS | 0.624383 | 0.341547 | 807.0 | 10.2% | Advanced Electric Appliances | Japan - JPN |
| DiRe | 0.595087 | 0.333157 | 945.2 | 8.8% | CSS Bio | Greece - GRC |
| HWTP | 0.548806 | 0.212225 | 278.6 | 22.1% | Biofuels | Japan - JPN |
| SWUC | 0.669119 | 0.374991 | 803.9 | 10.2% | Advanced Electric Appliances | Greece - GRC |

## Allocation sanity

| Scenario | Budget OK | Cap OK | Score/allocation corr | PD/allocation corr |
|---|---|---|---:|---:|
| DAPS | True | True | 0.652 | -0.361 |
| DiRe | True | True | 0.673 | -0.362 |
| HWTP | True | True | 0.481 | -0.221 |
| SWUC | True | True | 0.658 | -0.391 |

## Loss Distribution

| Scenario | Mean loss | VaR 95% | VaR 99% | ES 95% | ES 99% |
|---|---:|---:|---:|---:|---:|
| DAPS | 10.83% | 34.57% | 44.06% | 40.74% | 49.45% |
| DiRe | 10.58% | 31.88% | 40.52% | 37.31% | 45.21% |
| HWTP | 6.76% | 21.00% | 29.26% | 26.15% | 33.58% |
| SWUC | 13.27% | 43.83% | 58.12% | 53.87% | 71.53% |

## Sensitivity To r

| r | Scenario | Capital-weighted PD | Mean loss | Effective obligors | Top 20 share | Top sector |
|---:|---|---:|---:|---:|---:|---|
| 0.0% | DAPS | 0.395654 | 10.37% | 155.4 | 29.40% | CSS Bio |
| 0.0% | DiRe | 0.390168 | 10.34% | 203.6 | 23.87% | CSS Bio |
| 0.0% | HWTP | 0.216604 | 5.91% | 131.2 | 34.06% | Biofuels |
| 0.0% | SWUC | 0.436464 | 13.07% | 149.6 | 30.19% | CSS Bio |
| 1.0% | DAPS | 0.371244 | 10.49% | 319.7 | 19.07% | Advanced Electric Appliances |
| 1.0% | DiRe | 0.364271 | 10.41% | 422.6 | 15.18% | CSS Bio |
| 1.0% | HWTP | 0.208880 | 6.13% | 167.9 | 29.81% | Biofuels |
| 1.0% | SWUC | 0.407893 | 13.19% | 302.6 | 19.76% | CSS Bio |
| 2.0% | DAPS | 0.341014 | 10.62% | 806.3 | 10.22% | Advanced Electric Appliances |
| 2.0% | DiRe | 0.332872 | 10.49% | 956.0 | 8.50% | Advanced Electric Appliances |
| 2.0% | HWTP | 0.212764 | 6.82% | 280.0 | 21.99% | Biofuels |
| 2.0% | SWUC | 0.374110 | 13.33% | 800.3 | 10.32% | CSS Bio |
| 3.0% | DAPS | 0.315126 | 10.70% | 1415.6 | 6.09% | Advanced Electric Appliances |
| 3.0% | DiRe | 0.306828 | 10.54% | 1583.8 | 5.23% | Advanced Electric Appliances |
| 3.0% | HWTP | 0.218026 | 7.55% | 579.2 | 14.35% | Biofuels |
| 3.0% | SWUC | 0.345960 | 13.40% | 1399.4 | 6.03% | Advanced Electric Appliances |
| 4.0% | DAPS | 0.296960 | 10.74% | 1830.3 | 4.14% | Advanced Electric Appliances |
| 4.0% | DiRe | 0.288552 | 10.57% | 2006.7 | 3.61% | Advanced Electric Appliances |
| 4.0% | HWTP | 0.217506 | 8.00% | 971.2 | 10.06% | Equipment for wind power technology |
| 4.0% | SWUC | 0.326476 | 13.43% | 1758.1 | 4.08% | Non-metallic minerals |
| 5.0% | DAPS | 0.284428 | 10.76% | 2034.0 | 3.12% | Non-metallic minerals |
| 5.0% | DiRe | 0.275898 | 10.58% | 2217.0 | 2.74% | Non-metallic minerals |
| 5.0% | HWTP | 0.215099 | 8.28% | 1350.1 | 7.60% | Equipment for wind power technology |
| 5.0% | SWUC | 0.313118 | 13.45% | 1907.8 | 3.07% | Non-metallic minerals |

## Top sectors: DAPS

| Sector | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Advanced Electric Appliances | 3.825 | 0.553282 | 0.015820 |
| CSS Bio | 3.236 | 0.601627 | 0.012713 |
| Equipment for wind power technology | 3.215 | 0.585457 | 0.014048 |
| Non-metallic minerals | 3.019 | 0.540781 | 0.015423 |
| Biomass Solid | 2.727 | 0.651880 | 0.011398 |
| Hydrogen | 2.657 | 0.611945 | 0.013171 |
| Oil | 2.647 | 0.590878 | 0.013613 |
| Wind | 2.624 | 0.585361 | 0.013279 |
| Non Market Services | 2.613 | 0.499002 | 0.015179 |
| Power Supply | 2.586 | 0.596789 | 0.012911 |

## Top sectors: DiRe

| Sector | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| CSS Bio | 3.252 | 0.571734 | 0.013669 |
| Advanced Electric Appliances | 3.242 | 0.555647 | 0.015724 |
| Hydro electric | 2.916 | 0.576694 | 0.014281 |
| Equipment for wind power technology | 2.894 | 0.580667 | 0.014291 |
| Non-metallic minerals | 2.711 | 0.528548 | 0.015829 |
| Wind | 2.694 | 0.555019 | 0.014388 |
| Biomass Solid | 2.614 | 0.648298 | 0.011824 |
| Oil | 2.573 | 0.583384 | 0.014022 |
| Hydrogen | 2.510 | 0.576242 | 0.014507 |
| Oil Fired | 2.470 | 0.650883 | 0.012627 |

## Top sectors: HWTP

| Sector | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Biofuels | 8.091 | 0.441419 | 0.020261 |
| Equipment for wind power technology | 6.411 | 0.402259 | 0.021727 |
| Biomass | 5.948 | 0.391900 | 0.021729 |
| Wind | 5.013 | 0.382609 | 0.021153 |
| EV Transport Equipment | 4.884 | 0.468179 | 0.019032 |
| Equipment for PV panels | 4.766 | 0.429926 | 0.019438 |
| Batteries | 3.431 | 0.579785 | 0.014585 |
| Hydrogen | 3.367 | 0.509135 | 0.017316 |
| Biomass Solid | 3.003 | 0.528211 | 0.016126 |
| Geothermal | 2.986 | 0.505783 | 0.016979 |

## Top sectors: SWUC

| Sector | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Advanced Electric Appliances | 3.472 | 0.615665 | 0.013552 |
| CSS Bio | 3.461 | 0.630794 | 0.011654 |
| Hydro electric | 3.236 | 0.638175 | 0.012215 |
| Biomass Solid | 3.120 | 0.652232 | 0.011431 |
| Equipment for wind power technology | 3.069 | 0.635103 | 0.012266 |
| Wind | 3.015 | 0.616933 | 0.012265 |
| Construction | 2.824 | 0.664592 | 0.010992 |
| Oil Fired | 2.814 | 0.692307 | 0.011072 |
| Hydrogen | 2.742 | 0.632885 | 0.012529 |
| Non-metallic minerals | 2.662 | 0.611245 | 0.012931 |

## Top regions: DAPS

| Region | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Japan - JPN | 3.812 | 0.590988 | 0.014257 |
| Greece - GRC | 3.342 | 0.635909 | 0.012471 |
| United Kingdom - GBR | 3.286 | 0.576220 | 0.013770 |
| Netherlands - NLD | 3.228 | 0.551259 | 0.015531 |
| Portugal - PRT | 3.148 | 0.558044 | 0.013900 |
| Saudi Arabia - SAU | 3.068 | 0.589847 | 0.013484 |
| Germany - DEU | 2.858 | 0.542957 | 0.015050 |
| Rest of Europe | 2.793 | 0.567675 | 0.014069 |
| South Africa - ZAF | 2.773 | 0.575355 | 0.013454 |
| Brazil - BRA | 2.744 | 0.577421 | 0.014072 |

## Top regions: DiRe

| Region | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Greece - GRC | 3.314 | 0.623450 | 0.013077 |
| Luxembourg - LUX | 3.186 | 0.480947 | 0.017452 |
| Denmark - DNK | 3.104 | 0.564889 | 0.014685 |
| Japan - JPN | 2.977 | 0.595183 | 0.014102 |
| Russia - RUS | 2.927 | 0.645754 | 0.012873 |
| Brazil - BRA | 2.831 | 0.561597 | 0.014683 |
| Portugal - PRT | 2.704 | 0.549517 | 0.014159 |
| United Kingdom - GBR | 2.649 | 0.583096 | 0.013660 |
| Rest of Europe | 2.594 | 0.538617 | 0.014982 |
| Malta - MLT | 2.569 | 0.558546 | 0.015038 |

## Top regions: HWTP

| Region | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Japan - JPN | 6.583 | 0.502665 | 0.018184 |
| Argentina - ARG | 5.007 | 0.591980 | 0.014408 |
| Rest of Energy Producing Countries | 4.825 | 0.480678 | 0.017650 |
| Canada - CAN | 4.316 | 0.587774 | 0.015192 |
| Turkey - TUR | 4.031 | 0.547595 | 0.015190 |
| Saudi Arabia - SAU | 3.247 | 0.524562 | 0.016446 |
| United Kingdom - GBR | 3.195 | 0.526909 | 0.015897 |
| Russia - RUS | 3.145 | 0.592102 | 0.014944 |
| Brazil - BRA | 3.056 | 0.528347 | 0.016057 |
| Spain - ESP | 2.819 | 0.563891 | 0.014493 |

## Top regions: SWUC

| Region | Total capital | Avg PD | Avg score |
|---|---:|---:|---:|
| Greece - GRC | 3.823 | 0.664605 | 0.011520 |
| Denmark - DNK | 3.187 | 0.621185 | 0.012682 |
| Luxembourg - LUX | 3.180 | 0.545717 | 0.014762 |
| Malta - MLT | 3.141 | 0.612512 | 0.013165 |
| Japan - JPN | 3.005 | 0.647621 | 0.012261 |
| United Kingdom - GBR | 2.968 | 0.652948 | 0.011458 |
| Austria - AUT | 2.908 | 0.650208 | 0.011568 |
| Spain - ESP | 2.785 | 0.659870 | 0.010663 |
| Portugal - PRT | 2.776 | 0.604875 | 0.012242 |
| Germany - DEU | 2.693 | 0.597112 | 0.013165 |
