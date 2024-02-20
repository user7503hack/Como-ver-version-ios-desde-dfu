# Como-ver-version-ios-desde-dfu
1. Abre la Terminal en tu Mac.

2. Si no tienes instalado Homebrew, puedes instalarlo ejecutando el siguiente comando en la Terminal:

   ```shell
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```

3. Una vez que tengas Homebrew instalado, puedes instalar libimobiledevice con el siguiente comando:

   ```shell
   brew install --HEAD libimobiledevice
   ```

4. Después de que la instalación se complete, intenta nuevamente ejecutar el comando ideviceinfo:

   ```shell
   ideviceinfo -k ProductType -k ProductVersion
   ```
