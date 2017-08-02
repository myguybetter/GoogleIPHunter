# Google IP Hunter

![progress](http://progressed.io/bar/27?title=progress)

This project, GoogleIPHunter, is mainly for collecting global google ipv4 addresses. Mostly Google Global Cache IPs (GGC), also with Official IPs.

GGC only provides with two kinds of certificates (gws - google.com & gvs - googlevideo.com).

You can check Google's Official GGC Distribution Map here: https://peering.google.com/#/infrastructure

## How you hunt for them?

By online searching.

## How to Use?

Try to scan the IP ranges by using multiple IP scanning tools (like gscan, gogotester etc.). Both available **gws** and **gvs** ips can be used in Google Cloud Engine Proxy Tools (goagent, goproxy etc.), but only **gws** ips can be used by hosts file (not recommended due to the new strategy of national firewall to block Google IPs).

## Current Progress

### 1. Asia Pacific (56 checked)

- 43 Owning GGC Countries & Areas

| Countries & Areas | Total | Countries & Areas | Total | Countries & Areas | Total |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Armenia    | 13 | Israel      | 22 | Pakistan            | 44 |
| Azerbaijan | 14 | Japan       | 40 | Palestine           | 8  |
| Bahrain    | 10 | Jordan      |  9 | Philippines         | 32 |
| Bangladesh | 70 | Kazakhstan  | 38 | Qatar               |  6 |
| Bhutan     |  1 | Kuwait      | 20 | Russia             | 321 |
| Brunei     |  2 | Kyrgyzstan  | 10 | Singapore           | 14 |
| Cambodia   | 23 | Laos        |  4 | South Korea         | 49 |
| China<sup>1</sup>    | 21 | Lebanon     | 20 | Sri Lanka           |  6 |
| Cyprus     | 5  | Macao       |  3 | Taiwan              | 59 |
| Egypt      | 22 | Malaysia    | 35 | Thailand            | 75 |
| Georgia    | 11 | Maldives    |  3 | Turkey              |  1 |
| Hong Kong  | 17 | Mongolia    | 10 | United Arab Emirates | 2 |
| India     | 109 | Nepal       |  6 | Vietnam             | 83 |
| Indonesia  | 84 | Oman        |  4 | Yemen               |  1 |
| Iraq       | 68 |

- 13 No GGC Countries & Areas

Afghanistan, British Indian Ocean Territory, Christmas Island, Cocos Islands, Iran, Myanmar, North Korea, Saudi Arabia, Syria, Tajikistan, Timor-Leste, Turkmenistan, Uzbekistan.

<sup>1</sup> Most ips of this country couldn't be used due to 404 error (not found).
