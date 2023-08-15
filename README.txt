I wrote this mod primarily for my co-op playthrough with my wife. Figured I'd publish it -- someone might like it.

This mod provides a toggleable Lone Wolf Mode passive, located in your character sheet under the Common tab(see attached images). This toggle provides the following benefits:

    1 additional Action charge
    Increased hit points by 30%
    Increased carrying capacity by 50%
    1d4 bonus to all d20 rolls
    More frequent use of their weapon actions (Once per Battle, as compared to Once per Short Rest)
      - NOTE: I have not yet tied the Weapon Action modifications to the toggle. If you install this mod, this particular feature will be enabled by default.


This mod was written to faithfully represent a Baldur's Gate 3 interpretation of Divinity: Original Sin 2's Lone Wolf feature. Keep in mind that while this mod is -intended- to be used with only 2 character's in your party -- there is nothing stopping you from using this in a full party.

This mod requires the Full Release Mod Fixer [https://www.nexusmods.com/baldursgate3/mods/550] and I highly recommend installing it via LaughingLeader's Baldur's Gate 3 Mod Manager [https://github.com/LaughingLeader/BG3ModManager]

For manual installation, please add the following lines to your modsettings.lsx file located at: C:\Users\<USERID>\AppData\Local\Larian Studios\Baldur's Gate 3\PlayerProfiles\Public -- place the code below within the <children> grouping under <node id="Mods">

<node id="ModuleShortDesc">
  <attribute id="Folder" value="LoneWolf" type="LSString" />
  <attribute id="MD5" value="" type="LSString" />
  <attribute id="Name" value="Lone Wolf Mode" type="LSString" />
  <attribute id="UUID" value="78bad612-501b-42d4-9652-c384acfecaaf" type="FixedString" />
  <attribute id="Version64" value="36028797018963968" type="int64" />
</node>