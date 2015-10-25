#TPP.FileFormats
Fox Engine / Metal Gear Solid V: The Phantom Pain file format research dump.

##References
These are tools that were originally created to unpack and repack Metal Gear Solid V: Ground Zeroes (PC) files. These might work with the file formats used in The Phantom Pain.

[GzsTool](https://github.com/Atvaark/GzsTool)

[FtexTool](https://github.com/Atvaark/FtexTool)

[FoxTool](https://github.com/Atvaark/FoxTool)

[FoxEngine.TranslationTool](https://github.com/Atvaark/FoxEngine.TranslationTool)

[MGSV QAR Tool v1.3 by Sergeanur](https://www.dropbox.com/s/0rtpumx2mxsjaby/MGSV_QAR_Tool.rar?dl=0)

[MGSV FPK Tool v1.1 by Sergeanur](https://www.dropbox.com/s/8g8qg35jmluqqlx/MGSV_FPK_Tool.rar?dl=0)

## Files and file formats
### Files by platform
| Platform           | Files                                  |
| ------------------ | -------------------------------------- |
| PC                 | [See files_pc.md](files_pc.md)         |
| Playstation 3      | [See files_ps3.md](files_ps3.md)       |
| Xbox 360           | [See files_360.md](files_360.md)       |

### Versions
| Platform           | Versions                               |
| ------------------ | -------------------------------------- |
| PC                 | [See versions_pc.md](versions_pc.md)   |

### Files with associated tools
| Extension          | Description                            | Associated tools                             |
| ------------------ | -------------------------------------- | -------------------------------------------- |
| .lua               | Script                                 | Your preferred text editor                   |
| .json              | Settings                               | Your preferred text editor                   |
| .xml               | Settings                               | Your preferred text editor                   |
| .fpk               | Archive                                | GzsTool                                      |
| .fpkd              | Archive                                | GzsTool                                      |
| .pftxs             | Texture archive                        | GzsTool                                      |
| .sbp               | Sound archive                          | GzsTool                                      |
| .qar               | Archive                                | GzsTool                                      |
| .qar               | Archive                                | MGSV QAR Tool 1.3                            |
| .fpk               | Archive                                | MGSV FPK Tool 1.1                            |
| .fpkd              | Archive                                | MGSV FPK Tool 1.1                            |
| .ftex              | Texture head                           | FtexTool                                     |
| .ftexs             | Texture data                           | FtexTool                                     |
| .bnd               | Graph bounder data                     | FoxTool                                      |
| .clo               | Cloth settings                         | FoxTool                                      |
| .des               | Destruction settings                   | FoxTool                                      |
| .evf               | Event settings                         | FoxTool                                      |
| .fox2              | Scene settings                         | FoxTool                                      |
| .fsd               | Facial settings                        | FoxTool                                      |
| .ph                | Physics object settings                | FoxTool                                      |
| .phsd              | Physics sound settings                 | FoxTool                                      |
| .sdf               | Sound data file info                   | FoxTool                                      |
| .sim               | Simulation object settings             | FoxTool                                      |
| .parts             | Model parts settings                   | FoxTool                                      |
| .tgt               | Geometry target settings               | FoxTool                                      |
| .veh               | Vehicle driving settings               | FoxTool                                      |
| .lad               | Lip adjust settings                    | FoxTool                                      |
| .subp              | Subtitles                              | FoxEngine.TranslationTool                    |
| .ffnt              | Bitmap font                            | FoxEngine.TranslationTool                    |
| .lng               | String table                           | FoxEngine.TranslationTool                    |
| .lng2              | String table                           | FoxEngine.TranslationTool                    |

###General formats
| Extension          | Associated tools                             |
| ------------------ | -------------------------------------------- |
| .ag.evf            |                                              |
| .aia               |                                              |
| .aib               |                                              |
| .aibc              |                                              |
| .aig               |                                              |
| .aigc              |                                              |
| .ladb              |                                              |
| .aim               |                                              |
| .aip               |                                              |
| .ait               |                                              |
| .atsh              |                                              |
| .bnd               | FoxTool                                      |
| .cc.evf            |                                              |
| .clo               | FoxTool                                      |
| .des               | FoxTool                                      |
| .ese               |                                              |
| .evb               |                                              |
| .evf               | FoxTool                                      |
| .fag               |                                              |
| .fage              |                                              |
| .fago              |                                              |
| .fagp              |                                              |
| .fagx              |                                              |
| .fclo              |                                              |
| .fcnp              |                                              |
| .fcnpx             |                                              |
| .fdes              |                                              |
| .fdmg              |                                              |
| .fmdl              |                                              |
| .fnt               |                                              |
| .fova              |                                              |
| .fox               |                                              |
| .fox2              | FoxTool                                      |
| .fpk               | MGSV FPK Tool 1.1 or GzsTool                 |
| .fpkd              | MGSV FPK Tool 1.1 or GzsTool                 |
| .fpkl              |                                              |
| .frdv              |                                              |
| .frig              |                                              |
| .frt               |                                              |
| .fsd               | FoxTool                                      |
| .fsm               |                                              |
| .fsml              |                                              |
| .fstb              |                                              |
| .ftex              | FtexTool                                     |
| .ftexs             | FtexTool                                     |
| .fx.evf            |                                              |
| .fxp               |                                              |
| .gani              |                                              |
| .geom              |                                              |
| .gpfp              |                                              |
| .grxla             |                                              |
| .grxoc             |                                              |
| .gskl              |                                              |
| .htre              |                                              |
| .json              | Any text editor                              |
| .lad               | FoxTool                                      |
| .lani              |                                              |
| .las               |                                              |
| .lba               |                                              |
| .lng               | FoxEngine.TranslationTool                    |
| .lng2              | FoxEngine.TranslationTool                    |
| .lpsh              |                                              |
| .lua               | Any text editor                              |
| .mas               |                                              |
| .mog               |                                              |
| .mtar              |                                              |
| .mtl               |                                              |
| .nav2              |                                              |
| .obr               |                                              |
| .obrb              |                                              |
| .parts             | FoxTool                                      |
| .path              |                                              |
| .pftxs             | GzsTool                                      |
| .ph                | FoxTool                                      |
| .phep              |                                              |
| .phsd              | FoxTool                                      |
| .rbs               |                                              |
| .rdb               |                                              |
| .rdf               |                                              |
| .sad               |                                              |
| .sani              |                                              |
| .sbp               | GzsTool                                      |
| .spch              |                                              |
| .sd.evf            |                                              |
| .sdf               | FoxTool                                      |
| .sim               | FoxTool                                      |
| .simep             |                                              |
| .sub               |                                              |
| .subp              | FoxEngine.TranslationTool                    |
| .tgt               | FoxTool                                      |
| .tre2              |                                              |
| .txt               |                                              |
| .uia               |                                              |
| .uif               |                                              |
| .uig               |                                              |
| .uigb              |                                              |
| .uil               |                                              |
| .uilb              |                                              |
| .utxl              |                                              |
| .veh               | FoxTool                                      |
| .vfx               |                                              |
| .vfxbin            |                                              |
| .vfxdb             |                                              |
| .vo.evf            |                                              |
| .wem               |                                              |
| .xml               | Any text editor                              |
| .ffnt              | FoxEngine.TranslationTool                    |
| .fsop              |                                              |
| .fv2               |                                              |
| .1.nav2            |                                              |
| .csnav             |                                              |
| .vnav              |                                              |
| .dnav              |                                              |
| .snav              |                                              |
| .rnav              |                                              |
| .info              |                                              |
| .fmdlb             |                                              |
| .dnav2             |                                              |
| .mbl               |                                              |
| .sand              |                                              |
| .qar               | MGSV QAR Tool 1.3 or GzsTool                 |
| .nta               |                                              |
