### WORK REPORT

<sub>Website</sub>

```
https://tts.intra.ais
```

<sub>Detail Activity</SUB>
<sub>Activity Title</sub>

```
PS24.4.1 Deploy myOffice New Inventory (VHL) on 20240403
```

<sub>Description/Objective</sub>

```
นำโปรแกรมขึ้น deploy production
```

<sub>System Group</sub>

```
BSS - Business Support System
```

<sub>Activity Group</sub>

```
Deploy Application
```

<sub>Activity scope</sub>

```
New Service/Feature
```

<sub>Add Node</sub>

```
PNEWINVA801G
PNEWINVA802G
PNEWINVA803G
PNEWINVW801G
PNEWINVW802G
```

<sub>Application</sub>

```
myOffice
```

<sub>Component</sub>

```
New Inventory
```

<sub>Time Activity</SUB>
<sub>Activity Start Date - Activity End Date</sub>

```
02/04/2024 22:00 - 03/04/2024 02:00
```

<sub>Execute Start Date - Execute End Date</sub>

```
02/04/2024 22:00 - 03/04/2024 02:00
```

<sub>Contact point</sub>
<sub>Contact Point</sub>

```
thanakrk@ais.co.th
```

<sub>Decision Risk</sub>
<sub>Likelihood of Unplanned outage</sub>

```
2: System no error last 12 month
```

<sub>Impact of Unplanned outage</sub>

```
1: Minor
```

<sub>Worst Service Impact</sub>

```
หากรันแอพไม่ขึ้น ให้กลับไปใช้ version ก่อนหน้านี้
```

<sub>Send to Manager</sub>
<sub>Authorize Manager</sub>

```
Supakorn Thanikphithak (บูม)
Annis    Abdulhakim    (นีส)
Unn      Chanchaeng    (อัญ)
```

### NEXUS

<sub>Website</sub>

```
https://repo1.matador.ais.co.th/#browse/welcome
```

<sub>App Config</sub>

```
File        : conf-app-1.0.0-20240403
Group ID    : conf-phx
Artifact ID : conf-app
Vsersion    : 1.0.0-20240403
```

<sub>Web Config</sub>

```
File        : conf-web-1.0.0-20240403
Group ID    : conf-phx
Artifact ID : conf-web
Vsersion    : 1.0.0-20240403
```

<sub>App Server</sub>

```
File        : phxinvapp-1.0.0-20240403
Group ID    : app
Artifact ID : phxinvapp
Vsersion    : 1.0.0-20240403
```

<sub>Web Server</sub>

```
File        : phxinvweb-1.0.0-20240403
Group ID    : web
Artifact ID : phxinvweb
Vsersion    : 1.0.0-20240403
```

### PRETEST

```LOG
REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-cecilia/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/cecilia/style?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-mvpn/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/mvpn/call-screening?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-nas-portal/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/nasportal/nas-portal-mo?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-number-mangement/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-admin/number-management/number-admin?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-customer-portal/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/customer-portal/asset?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-admin/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/admin/admin-all-around?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-wpp/-/commits/master2
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/wpp/inquiry-cash-card?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-new-wpp/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/new-wpp/wpp-production-control?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-order/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/myoffice/price-plan/plan-management?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-inventory/-/commits/prod
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/inventory/fraud-number?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-portal/-/commits/master
LINK: https://localhost:8443/phx-inventory/portal/portal-management?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/phx-client-s3/-/commits/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-s3/s3/s3-viewer?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/mo-client-universe/-/tree/master
LINK: https://localhost:8443/phx-inventory/auth/signin-sff/phx-inventory/universe/inventory/sim/inquiry-sim?sffToken=$MOKEN

REPO: https://git.matador.ais.co.th/vhlinventory/contract-management/ctmclient/-/tree/iot
LINK: https://localhost:8443/phx-inventory/auth/signin-ctm/phx-inventory/contract-management-ctm/customer-contract-profile?sffToken=$MOKEN
```