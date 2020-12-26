# Open core EFI for [LG Gram 14z980](https://www.amazon.in/LG-Ultra-Light-Processor-Generation-Professional/dp/B07WPVHCXM/ref=sr_1_2?dchild=1&keywords=lg+gram+14&qid=1608990365&refinements=p_n_pattern_browse-bin%3A1464445031%2Cp_89%3ALG%2Cp_n_feature_thirteen_browse-bin%3A12598162031&rnid=12598141031&s=computers&sr=1-2)

## Before you install 
  * Change the Serial number
  * Modify the BIOS settings (press F2 to enter the BIOS when booting, Ctrl + Alt + F7 to open the hidden BIOS options, thanks to [as695336480](https://github.com/capricornlee/LG-Gram13-Z990/issues/7#issue-624133249) for providing: source)
The following is provided by linGinc, thanks!
      1. BIOS-Main-Boot Features: CMS Support [No], Fast Boot [Disabled]
      1. BIOS-Advanced-Intel Advanced Menu-Power&Performance-CPU Power Management Control: CFG Lock [Disabled]
      1. BIOS-Advanced-System Agent(SA) Configuration: VT-d [Disabled], Above 4GB MMIO BIOS assignment [Enabled]
      1. BIOS-Advanced-System Agent(SA) Configuration-Graphics Configuration: DVMT Pre-Allocated [64M]
    
## This is what works
  * Battery patched
  * Trackpad 
  * Wifi and bluetooth using airportitilwm
    * Handoff  
    * universal clipboard
  * Side car (using wire)
  * Sleep works
  * If you want working function keys for brightness to work follow the tutorial posted by [suzuke](https://github.com/suzuke/LG-Gram-13z980-Opencore)

## This will not work
  * The airplay and wireless sidecar
  * iService may work 
  * Airdrop also won't work
  * haven't tested sd card and hdmi port
  * Also no fan speed 

## Credits
  * Thanks [suzuke](https://github.com/suzuke/LG-Gram-13z980-Opencore) for battery ssdt
  * Thanks [Open Wireless community](https://github.com/OpenIntelWireless) for bluetooth and wifi 
  * Thanks [Opencore community](https://github.com/acidanthera/OpenCorePkg) 
  
