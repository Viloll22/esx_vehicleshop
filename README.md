# esx_vehicleshop

## Requisitos

* Modo automático (todos pueden comprar vehículos en el concesionario)
  * No es necesario descargar otro recurso

* Gestión de jugadores (el trabajo del concesionario de coches): facturación, acciones del jefe y más.
  * [esx_society] (https://github.com/ESX-Org/esx_society)
  * [esx_billing] (https://github.com/ESX-Org/esx_billing)
  * [esx_addonaccount] (https://github.com/ESX-Org/esx_addonaccount)
  * [esx_addoninventory] (https://github.com/ESX-Org/esx_addoninventory)
  * [cron] (https://github.com/ESX-Org/cron)

## Instalación
- Importa `esx_vehicleshop.sql` a tu base de datos
- Agregue esto en su `server.cfg`:

  ensure esx_vehicleshop

- Si desea administrar el concesionarior, debe configurar `Config.EnablePlayerManagement` en` true` en` config.lua`

# Legal
### Licencia
esx_vehicleshop - tienda de vehículos para ESX

Copyright (C) 2015-2018 Jérémie N'gadi

Este programa es software libre: puede redistribuirlo y / o modificarlo según los términos de la licencia pública general GNU publicada por la Free Software Foundation, ya sea la versión 3 de la licencia, o (a su elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil, pero SIN NINGUNA GARANTÍA; incluso sin la garantía implícita de COMERCIABILIDAD O APTITUD PARA UN PROPÓSITO PARTICULAR. Consulte la Licencia pública general GNU para obtener más detalles.

Debería haber recibido una copia de la Licencia Pública General GNU junto con este programa. De lo contrario, consulte http://www.gnu.org/licenses/.
