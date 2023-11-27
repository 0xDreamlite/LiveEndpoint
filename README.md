### WARP Endpoint IP Finder

--------------------------------------------------------------------------
**Original author of the article:** [MisakaNo](https://blog.misaka.rest/)
**Article link:** https://blog.misaka.rest/2023/03/12/cf-warp-yxip/
--------------------------------------------------------------------------
## مراحل ترجیحی

توجه: لطفاً هر نرم افزار پروکسی VPN را خاموش کنید، در غیر این صورت نتایج ترجیحی ممکن است نادرست باشد! ! !

## Preferred steps

Note: Please turn off any VPN proxy software, otherwise the preferred results may be inaccurate! ! !

### Linux

1: Enter the command line and copy and paste the following command

1: وارد ترمینال شده و دستور زیر را کپی و پیست کنید

```shell
wget -N https://raw.githubusercontent.com/DreamXlite/LiveEndpoint/main/LiveEndpoint.sh && bash LiveEndpoint.sh
```

2:Select the preferred mode (default is IPv4)


2:حالت ترجیحی را انتخاب کنید (پیش فرض IPv4 است)

3: Wait for the script to install dependencies and select


3: منتظر بمانید تا اسکریپت نصب شود و انتخاب کنید


4: The script will automatically display the top 10 best WARP Endpoint IPs



4: اسکریپت به طور خودکار 10 IP برتر WARP Endpoint را نمایش می دهد

### Android

1: Install and open Termux, copy and paste the following command

1: ترموکس را نصب و باز کنید، دستور زیر را کپی و پیست کنید

```shell
wget -N https://raw.githubusercontent.com/DreamXlite/LiveEndpoint/main/LiveEndpoint.sh && bash LiveEndpoint.sh
```

# Android Termux If there is no wget, please use the following command to install it


# کاربر ترموکس اگر wget وجود ندارد، لطفا از دستور زیر برای نصب آن استفاده کنید
```shell
pkg update && pkg install wget
```

2:Select the preferred mode (default is IPv4)


2:حالت ترجیحی را انتخاب کنید (پیش فرض IPv4 است)

3: Wait for the script to install dependencies and select


3: منتظر بمانید تا اسکریپت نصب شود و انتخاب کنید


4: The script will automatically display the top 10 best WARP Endpoint IPs



4: اسکریپت به طور خودکار 10 IP برتر WARP Endpoint را نمایش می دهد



If you receive an error, you can use the following code to fix it and do everything from the beginning


اگر خطا دریافت کردید میتوانید از کد زیر برای رفع استفاده کنید و از اول همه چیز را انجام بدید

```shell
rm -f ./warp && bash LiveEndpoint.sh
```
