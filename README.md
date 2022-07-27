Base form original edk2-porting/edk2-sm8150 

Oly for Boot Linux !

##
 Usb dxes need patch，usb will case uefi crash,So disabled them.
Windows not boot.
usb dxe需要补丁，插入usb会导致uefi crash，所以现在禁用了它

##
 Notice: you may need your xbl dxes
注意，一些dxe可能需要你自己解压替换


We are looking forward to your testing (即便你发了也没人理你)
Website: renegade-project.org
Forum: forum.renegade-project.org


## For devices in other resolution,
pls edit msmnile.dsc:
gF11TokenSpaceGuid.PcdMipiFrameBufferWidth|width
gF11TokenSpaceGuid.PcdMipiFrameBufferHeight|height

For Others devices,
pls edit build-xxx.sh，or replace dtb。
cat xxx.dtb >>

Have Fun.