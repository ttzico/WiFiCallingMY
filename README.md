# WiFiCallingMY

Malaysia Wi-Fi Calling (VoWiFi) routing rules.

## Supported Carrier

Currently verified:

- Hotlink Malaysia
- Maxis network
- MCC 502
- MNC 012

## Rule

The current rule set contains the verified Maxis ePDG hostname:

`epdg.epc.mnc012.mcc502.pub.3gppnetwork.org`

## Usage

### Surge

Add the following rule to the `[Rule]` section:

```ini
RULE-SET,https://raw.githubusercontent.com/LOWERTOP/WiFiCallingMY/main/WiFiCallingMY.list,🇲🇾 Malaysia
