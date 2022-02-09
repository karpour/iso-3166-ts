# ISO 3166 Typescript types

Typescript data type for ISO3166-alpha2 country codes, as well as mappings for country code => country name

## Examples

```typescript
import { getIso3166CountryName, isIso3166Alpha2Code, Iso3166Alpha2Code, ISO_3166_ALPHA_2 } from "iso-3166-ts";

const countryCode:Iso3166Alpha2Code = "NL";

isIso3166Alpha2Code("NL"); // true
isIso3166Alpha2Code("ZZ"); // false

getIso3166CountryName(countryCode); // 'Netherlands'

/** Array containing all ISO3166 Alpha 2 country codes */
const allCountryCodes:Iso3166Alpha2Code[] = ISO_3166_ALPHA_2;
```
