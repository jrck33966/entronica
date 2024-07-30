<!-- MOAPP    : 10.138.34.239 -->
<!-- root     : R3dh@t!@#     -->
<!-- serveradm: MO_219M6pP8j  -->

<!-- MOWEB    : 10.137.19.135 -->
<!-- root     : R3dh@t!@#     -->
<!-- serveradm: MO_219M6pP8j  -->

<!-- MOMDB    : 10.138.34.240 -->
<!-- root     : R3dh@t!@#     -->
<!-- serveradm: MO_219M6pP8j  -->

<!-- S3APP    : 10.138.21.222 -->
<!-- root     : R7G#pWy22     -->
<!-- serveradm: S3_uaF694Ua5  -->

<!-- S3PDB    : 10.138.21.223 -->
<!-- root     : R7G#pWy22     -->
<!-- moadm    : S3-4751z53j5  -->
<!-- postgres : S3-4751z53j5  -->
<!-- serveradm: S3_uaF694Ua5  -->

<!-- S3MDB    : 10.138.21.224 -->
<!-- root     : R7G#pWy22     -->
<!-- moadm    : S3-4751z53j5  -->
<!-- serveradm: S3_uaF694Ua5  -->
<!-- dockeradm: S3_uaF694Ua5  -->

<!-- JBAPP    : 10.138.38.59  -->
<!-- root     : R4j0VEi&5     -->
<!-- wppadm   :               -->
<!-- serveradm: Ais@30Jul     -->

<!-- JBPDB    : 10.138.38.60  -->
<!-- root     : R4j0VEi&5     -->
<!-- postgres : Ais@30Jul     -->
<!-- serveradm: Ais@30Jul     -->

### WEBSITE

#### STAGING

- [MO Portal](https://myoffice-web.intra.ais:8443/login)
- [MO Mail](https://10.252.160.41/owa)
- [SFF Portal](https://10.137.20.37:8103/SFFWeb/pages/home/portal.jsf)

#### PRODUCTION

- [MO Portal](https://myoffice-portal.intra.ais:8443/login)
- [MO Admin All Around](https://myoffice-portal.intra.ais:8443/phx-inventory/auth/signin-sff/phx-inventory/admin/admin-all-around?sffToken=)
- [Teleport](https://teleport1.ais.co.th)
- [TTS](https://tts.intra.ais)
- [Nexus](https://repo1.matador.ais.co.th/#browse/welcome)

#### OTHER

- [One Drive](https://mimotech-my.sharepoint.com)
- [Change Password](https://ovms-mmt.ais.co.th/osm/Pages/ChangePassword.aspx)

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
tatchaij@ais.co.th
thanakrk@ais.co.th
```

<sub>Service Impact</sub>
```
No impact
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

<sub>Fallback Strategy / Condition</sub>
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

#### ORACLE

```
INVSITDB =
  (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS =
          (COMMUNITY = TCP)
          (PROTOCOL = TCP)
          (HOST = 172.16.249.77)
          (PORT = 1537)))
    (CONNECT_DATA =
      (SID = INVSITDB)))

INVSITDB-INV =
  (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS =
          (COMMUNITY = TCP)
          (PROTOCOL = TCP)
          (HOST = 172.16.249.77)
          (PORT = 1537)))
    (CONNECT_DATA =
      (SID = INVSITDB)))

INVSITDB-MST =
  (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS =
          (COMMUNITY = TCP)
          (PROTOCOL = TCP)
          (HOST = 172.16.249.77)
          (PORT = 1537)))
    (CONNECT_DATA =
      (SID = INVSITDB)))

SFFSITDB =
  (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS =
          (COMMUNITY = TCP)
          (PROTOCOL = TCP)
          (HOST = 172.16.249.77)
          (PORT = 1536)))
    (CONNECT_DATA =
      (SID = SFFSITDB)))

TSTPPE2E =
  (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS =
          (COMMUNITY = TCP)
          (PROTOCOL = TCP)
          (HOST = 172.16.249.243)
          (PORT = 1551)))
    (CONNECT_DATA =
      (SID = TSTPPE2E)))
```

#### UBUNTU

```
# Golang
export PATH=$PATH:/usr/local/go/bin

# Node.js
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

# Oracle DB
export ORACLE_HOME=/opt/oracle/instantclient_19_22
export LD_LIBRARY_PATH=$ORACLE_HOME:$LD_LIBRARY_PATH
```

### INSTALLATION

#### POSGRES

```SH
podman volume create jb-postgresdb
podman run --rm -d -p 5432:5432 \
    -v jb-postgresdb:/var/lib/postgresql/data \
    -e POSTGRES_PASSWORD=postgres1234 \
    -e PGDATA=/var/lib/postgresql/data/pgdata \
    -e TZ=Asia/Bangkok \
    --name jb-postgresdb postgres:12.15

podman exec -it jb-postgresdb psql -h localhost -p 5432 -U postgres -c "CREATE DATABASE pvtwppdb;"
podman exec -it jb-postgresdb pg_dumpall -h 10.138.38.60 -p 5432 -U postgres -f /tmp/dump.sql
podman exec -it jb-postgresdb psql -h localhost -p 5432 -U postgres -f /tmp/dump.sql
podman exec -it jb-postgresdb cat /var/lib/postgresql/data/pgdata/postgresql.conf | grep Bangkok
podman cp jb-postgresdb:/tmp/dump.sql ./
```

#### MONGO

```SH
podman volume create mo-mongodb
podman run --rm -d -p 27037:27017 \
    -v mo-mongodb:/data/db \
    -e MONGO_INITDB_ROOT_USERNAME=dockeradm \
    -e MONGO_INITDB_ROOT_PASSWORD=dockeradm \
    --name mo-mongodb mongo:4.4.22 \
    --auth

podman exec -it mo-mongodb mongo -u dockeradm -p dockeradm --authenticationDatabase admin \
    --eval 'db.getSiblingDB("phx-inv-sit").createUser({ user: "phxinvStream", pwd: "phxinv2019", roles: [{ role: "readWrite", db: "phx-inv-sit" }] })'

mongodump -h 10.138.34.240:27017 -d phx-inv-sit -u phxinvStream -p phxinv2019 -c userWorkingHistoryReport -q '{ "createBy": "kamonphb" }'
mongorestore -h 10.138.21.224:27037 -d phx-inv-sit -u phxinvStream -p phxinv2019 dump/phx-inv-sit/userWorkingHistoryReport.bson
```

#### TIMESHEET

```SH
jq -r '.[] | "\(.["_id"]),\(.projectCode),\(.projectName),\(.functionCode),\(.functionDesc),\(.activeFlg)"' project.json | while IFS=, read -r _ID PROJECT_CODE PROJECT_NAME FUNCTION_CODE FUNCTION_DESC ACTIVE_FLG; do
    curl -s -k -X PUT "https://timesheet-ps.entro-lab.com/backend/api/project-function?_id=$_ID" \
    -H "Content-Type: application/json" \
    -d "{
        \"message\": {
            \"_id\": \"$_ID\",
            \"projectCode\" : \"$PROJECT_CODE\",
            \"projectName\" : \"$PROJECT_NAME\",
            \"functionCode\": \"$FUNCTION_CODE\",
            \"functionDesc\": \"$FUNCTION_DESC\",
            \"activeFlg\"   : \"N\"
        }
    }" | jq .
    sleep 1
done
```




