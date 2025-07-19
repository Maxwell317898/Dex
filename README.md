# DeX
>[!CAUTION]
>DeX has been tested and should NOT BE USED currently, as most exploits are not acted upon. </br>
>I am Working on a patch, expect this to be made by the 25th.

Deactivating eXploiters </br> </br>
Server side & Client side anti script execution
> [!NOTE]
> This Branch is on version 1 to see latest versions check out other `branches` </br>
## How does it work?
it works by looking out for if an item is added to the `localplayer` by using `item.ChildAdded` event, then DeX checks the type of the item (most exectutors inject `LocalScripts`) with `item.ClassName`, DeX disables the script from running useing `item.disabled = true`.
> [!IMPORTANT]
> DeX has not been tested as of yet by any exploit methods. Once tested, results will be posted.
## What I am working on.
adding a feature to veiw flagged items </br>
adding a feature to check that the localplayer script is still operational (and not disabled by an exploit)

> [!CAUTION]
> This measure of protection against exploitation comes with no warrenty, or 100% certenty of removing exploiters
