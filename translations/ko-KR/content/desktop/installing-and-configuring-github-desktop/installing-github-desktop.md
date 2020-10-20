---
title: 깃허브 데스크톱 설치
shortTitle: 설치
intro: 깃허브 데스크톱을 지원되는 윈도우와 맥OS 등의 운영시스템에 설치할 수 있습니다
redirect_from:
  - /desktop/getting-started-with-github-desktop/installing-github-desktop
versions:
  free-pro-team: '*'
---

### {% data variables.product.prodname_desktop %} 설치 관련

{% data variables.product.prodname_desktop %} 지원되는 운영시스템에 깃허브 데스크톱을 설치하실 수 있습니다. {% data variables.product.prodname_dotcom %} 또는 {% data variables.product.prodname_enterprise %}에 계정을 갖고 계신다면, {% data variables.product.prodname_desktop %}에 그 계정으로 접속이 가능하십니다. For more information about creating an account, see "[Signing up for a new {% data variables.product.prodname_dotcom %} account](/articles/signing-up-for-a-new-github-account/)" or contact your {% data variables.product.prodname_enterprise %} site administrator.

{% windows %}

If you are a network administrator, you can deploy {% data variables.product.prodname_desktop %} to computers running Windows on an Active Directory-managed network by using the Windows Installer package file (`.msi`) with Group Policy or another remote installation system.

The Windows Installer package extracts the standalone installer (`.exe`) and configures Windows to install {% data variables.product.prodname_desktop %} the next time a user signs in to their workstation. Users must have permissions to install {% data variables.product.prodname_desktop %} in their user directory.

If a user runs the Windows Installer package for {% data variables.product.prodname_desktop %} directly, to complete the installation, the user must sign out of their workstation and then sign back in.

{% endwindows %}

### Downloading and installing {% data variables.product.prodname_desktop %}

{% mac %}

You can install {% data variables.product.prodname_desktop %} on {% data variables.desktop.mac-osx-versions %}.

{% data reusables.desktop.download-desktop-page %}
2. Click **Download for macOS**. ![The Download for macOS button](/assets/images/help/desktop/download-for-mac.png)
3. In your computer's `Downloads` folder, double-click the **{% data variables.product.prodname_desktop %}** zip file. ![The GitHubDesktop.zip file](/assets/images/help/desktop/mac-zipfile.png)
4. After the file has been unzipped, double-click **{% data variables.product.prodname_desktop %}**.
5. {% data variables.product.prodname_desktop %} will launch after installation is complete.

{% endmac %}

{% windows %}

You can install {% data variables.product.prodname_desktop %} on {% data variables.desktop.windows-versions %}.

{% warning %}

**Warning**: You must have a 64-bit operating system to run {% data variables.product.prodname_desktop %}.

{% endwarning %}

{% data reusables.desktop.download-desktop-page %}
2. Click **Download for Windows**. ![The Download for Windows button](/assets/images/help/desktop/download-for-windows.png)
3. In your computer's `Downloads` folder, double-click the **{% data variables.product.prodname_desktop %}** setup file. ![The GitHubDesktopSetup file](/assets/images/help/desktop/windows-githubdesktopsetup.png)
4. {% data variables.product.prodname_desktop %} will launch after installation is complete.

{% endwindows %}
