# DeX
Deactivating eXploiters </br> </br>
Server side & Client side anti script execution
## How does it work?
it works by looking out for if an item is added to the `localplayer` by using `item.ChildAdded` event, then DeX checks the type of the item (most exectutors inject `LocalScripts`) with `item.ClassName`, DeX disables the script from running useing `item.disabled = true`.

## What I am working on.
adding a feature to veiw flagged items </br>
adding a feature to check that the localplayer script is still operational (and not disabled by an exploit)
