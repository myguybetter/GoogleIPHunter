# Google IP Hunter

**😀If you'd like to contribute, please *do not* hesitate to make a commit!**

This project 'GoogleIPHunter' is mainly for collecting global google ipv4 addresses. Mostly Google Global Cache IPs (GGC).

GGC IPs provide with 3 kinds of certs, including **"google.com (these ones could be applied to hosts)"**, **"*.googlevideo.com"** and **"edgestatic.com"**. ips with those certs above can be used in GAE like proxies (Goproxy, XX-net etc.).

You can check Google's Official GGC Distribution Map here: https://peering.google.com/#/infrastructure

**Caution: You could fork this project yourself, but please DO NOT distribute these contents to any other sites, or I would delete this repository. Thank you.**

## How do you hunt for them?

  - Zmap (ip port scanning tool) & [checkip.py](https://github.com/xyuanmu/checkiptools) (for checking Google ip) on my personal servers.
  - https://censys.io

## How to Use?

Try to scan the IP ranges by using multiple IP scanning tools (like gscan, gogotester etc.). Available IPs could be used.

## Current Progress (Will be updated soon)

Note: All countries & areas are collected from [wikipedia](https://en.wikipedia.org/wiki/List_of_sovereign_states_and_dependent_territories_by_continent).

### 1. Asia

| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Armenia		| 13 | Israel		| 22 | Pakistan			| 42 |
| Azerbaijan		| 14 | Japan		| 48 | Palestine		| 8  |
| Bahrain		| 10 | Jordan		|  9 | Philippines		| 31 |
| Bangladesh		| 70 | Kazakhstan	| 38 | Qatar			|  6 |
| Bhutan		|  1 | Kuwait		| 20 | Russia			| 326 |
| Brunei		|  2 | Kyrgyzstan	| 10 | Singapore		| 14 |
| Cambodia		| 23 | Laos		|  4 | South Korea		| 60 |
| China<sup>1</sup>	| 21 | Lebanon		| 20 | Sri Lanka		|  6 |
| Cyprus		| 5  | Macao		|  3 | Taiwan			| 61 |
| Egypt			| 22 | Malaysia		| 34 | Thailand			| 89 |
| Georgia		| 11 | Maldives		|  3 | Turkey			|  1 |
| Hong Kong		| 17 | Mongolia		| 10 | United Arab Emirates	 | 2 |
| India			| 109 | Nepal		|  6 | Vietnam			| 88 |
| Indonesia		| 84 | Oman		|  4 | Yemen			|  1 |
| Iraq			| 68 |

<sup>1</sup> *Most ips of this country couldn't be used due to 404 error (not found).*

### 2. North America

| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Aruba		| 1 | Curacao		| 1 | Jamaica		 | 5 |
| Bahamas	| 2 | Dominica		| 2 | Mexico		 | 135 |
| Barbados	| 5 | Dominican		| 9 | Nicaragua		 | 6 |
| Belize	| 1 | EI Salvador	| 5 | Panama		 | 9 |
| Bermuda	| 1 | Grenada		| 1 | Puerto Rico	 | 10 |
| Canada	| 106 | Guatemala	| 6 | Trinidad and Tobago| 6 |
| Cayman Islands| 2 | Haiti		| 3 | United States (GGC)| 354 |
| Costa Rica	| 13 | Honduras		| 8 | U.S. Virgin Islands| 1 |

### 3. South America

| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Argentina	| 109 | Colombia	| 30 | Suriname	| 1 |
| Bolivia	| 9 | Ecuador		| 32 | Uruguay	| 3 |
| Brazil	| 599 | Paraguay	| 5 | Venezuela	| 11 |
| Chile		| 43 | Peru		| 26 |

### 4. Europe

| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Aland			| 1 | Greece	| 11 | Montenegro	| 1 |
| Albania		| 7 | Guernsey	| 1 | Netherlands	| 15 |
| Austria		| 19 | Hungary	| 16 | Poland		| 73 |
| Belarus		| 4 | Iceland	| 8 | Portugal		| 13 |
| Belgium		| 5 | Ireland	| 8 | Romania		| 26 |
| Bosnia and Herzegovina		| 8 | Isle of Man	| 1 | Serbia		| 18 |
| Bulgaria		| 24 | Italy	| 28 | Slovak		| 12 |
| Croatia	| 5 | Jersey		| 1 | Slovenia		| 7 |
| Czech		| 15 | Latvia		| 10 | Spain		| 31 |
| Denmark		| 30 | Lithuania	| 16 | Sweden	| 29 |
| Estonia		| 3 | Luxembourg	| 1 | Ukraine	| 1 |
| Finland		| 9 | Macedonia		| 5 | Malta		| 6 |
| France		| 25 | Moldova		| 7 | Switzerland	| 19 |
| Germany		| 33 | Monaco		| 1 |

### 5. Africa
| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Algeria		| 6 | Kenya		| 7 | Rwanda	| 1 |
| Angola		| 3 | Lesotho	| 1 | Senegal	| 2 |
| Botswana		| 3 | Libya		| 2 | Seychelles| 1 |
| Cameroon		| 5 | Madagascar| 3 | Somalia	| 4 |
| Cape Verde	| 2 | Mali		| 1 | South Africa	| 17 |
| Djibouti		| 1 | Mauritius	| 7 | Tanzania	| 7 |
| Egypt			| 24 | Morocco	| 8 | Togo		| 1 |
| Ethiopia		| 1 | Mozambique| 4 | Tunisia	| 10 |
| Gabon			| 1 | Niger		| 2 | Uganda	| 5 |
| Ghana			| 5 | Nigeria	| 11 | Zambia	| 1 |
| Ivory Coast	| 2 | Réunion	| 4 | Zimbabwe	| 4 |

### 6. Oceania
| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Australia		| 62 | Guam		| 2 | Northern Mariana Islands	| 2 |
| Fiji			| 4 | New Caledonia	| 1 | Tonga		| 1 |
| French Polynesia | 1 | New Zealand | 31 | Vanuatu	| 1 |
