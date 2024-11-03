Commands of Bootloader
> U-Boot 1.1.3 (Dec 25 2017 - 22:59:38)

```
?       - alias for 'help'
bootm   - boot application image from memory
cp      - memory copy
erase   - erase SPI FLASH memory
go      - start application at address 'addr'
help    - print online help
loadb   - load binary file over serial line (kermit mode)
md      - memory display
mdio   - Ralink PHY register R/W command !!
mm      - memory modify (auto-incrementing)
nm      - memory modify (constant address)
printenv- print environment variables
reset   - Perform RESET of the CPU
rf      - read/write rf register
saveenv - save environment variables to persistent storage
setenv  - set environment variables
spi     - spi command
tftpboot- boot image via network using TFTP protocol
version - print monitor version
```

printenv
```
bootcmd=tftp
bootdelay=5
baudrate=57600
ethaddr="00:AA:BB:CC:DD:10"
ipaddr=10.10.10.123
serverip=10.10.10.3
stdin=serial
stdout=serial
stderr=serial
BootType=3

Environment size: 160/4092 bytes
```

Release:
```DISTRIB_ID="E-RUIKE"

DISTRIB_RELEASE="2.4"

DISTRIB_REVISION="unknown"

DISTRIB_CODENAME="ap21"

DISTRIB_TARGET="ramips/generic"

DISTRIB_DESCRIPTION="E-RUIKE AP21 2.4"

DISTRIB_TAINTS="no-all busybox"
```

Users:
```
e-ruike:x:0:0:root:/root:/bin/ash

root:x:0:0:root:/root:/bin/ash

daemon:*:1:1:daemon:/var:/bin/false

ftp:*:55:55:ftp:/home/ftp:/bin/false

network:*:101:101:network:/var:/bin/false

nobody:*:65534:65534:nobody:/var:/bin/false
```

Disk-Space:
```             total         used         free       shared      buffers

Mem:         61200        31480        29720            0         2712

-/+ buffers:              28768        32432

Swap:            0            0            0```

Mounts:
```
rootfs				on	/					type rootfs		(rw)
/dev/root			on	/rom				type squashfs	(ro,relatime)
proc				on	/proc				type proc		(rw,noatime)
sysfs				on	/sys				type sysfs		(rw,noatime)
tmpfs				on	/tmp				type tmpfs		(rw,nosuid,nodev,noatime)
/dev/mtdblock6		on	/overlay			type jffs2		(rw,noatime)
overlayfs:/overlay	on	/					type overlayfs	(rw,noatime,lowerdir=/,upperdir=/overlay)
tmpfs				on	/dev				type tmpfs		(rw,relatime,size=512k,mode=755)
devpts				on	/dev/pts			type devpts		(rw,relatime,mode=600,ptmxmode=000)
debugfs				on	/sys/kernel/debug	type debugfs	(rw,noatime)```

Top
```
Mem: 23600K used, 37600K free, 0K shrd, 2048K buff, 6388K cached
CPU:   0% usr   0% sys   0% nic  99% idle   0% io   % irq   0% sirq
Load average: 0.08 0.12 0.05 1/38 2006
 PID  PPID USER     STAT   VSZ %VSZ %CPU COMMAND
  762     1 e-ruike  S     1572   3%   0% /sbin/netifd
 1476     1 e-ruike  S     1532   3%   0% /usr/sbin/uhttpd -f -h /www -r E-RUIK
  385     1 e-ruike  S     1492   2%   0% -ash
 1903     1▒-ruike   S     1492   2%   0% {apReporterRun} /bin/sh /bin/apReport
 2006   385 e-ruike  R     1492   2%   0% top
  838     1 e-ruike  S     1492   2%   0% /usr/sbin/crond -f -c /etc/crontabs -
 1934     1 e-ruike  S     1488   2%   0% /usr/sbin/tpd -n -p 0.openwrt.pool.n
  956   762 e-ruike  S     1488   2%   0% udhcpc -p /var/run/udhcpc-eth0.2.pid
 1462     1 e-ruke   S     1484   2%   0% /usr/sbin/telnetd -F
 2005  1903 e-ruike  S     1480   2%   0% sleep 30
    1     0 e-ruike  S     1420   2%   0% /sbin/procd
  721     1 e-ruike  S     1048   2%   0% /sbin/logd -S 16
 1901     1 nobody   S      980   2%   0% /usr/sbin/dnsmasq -C /var/etc/dnsmasq
  382     1 e-ruike  S      888   1%   0% /sbin/ubusd
  519     1 e-ruike  S      768   1%   0% btnd wps 45
  518     1 e-ruike  S      768   1%   0% btnd reset 38
  520     1 e-ruike  S      768   1%   0% btnd wifi 46
    4     2 e-ruike  SW       0   0%   0% [kworker/0:0]
    3     2 e-ruike  SW       0   0%   0% [ksoftirqd/0]
    6     2 e-ruike  SW       0   0%   0% [kworker/u2:0]
```

CPU:
```
system type             : MT7628
machine                 : Unknown
processor               : 0
cp model                : MIPS 24KEc V5.5
BogoMIPS                : 382.46
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 32
extra interrupt vector  : yes
hardware watchpoint     : yes, count: 4, address/irw mask: [0x0ffc, 0x0ffc, 0x0ffb, 0x0ffb]
isa                     : mips1 mips2 mips32r1 mips32r2
ASEs implemented        : mips16 dsp
shadow register sets    : 1
kscratch registers      : 0
core                    : 0
VCED exceptions         : not available
VCEI exceptions         : not available
```