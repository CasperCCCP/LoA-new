# Changelog

## LoA 1.4.0.0 - EasyLOU 1.2.1.0 (12/01/2021)

#### Bugfixes:

- Fix version number - was supposed to be 1.2.1.0 [#146](https://github.com/Lady-Binary/EasyLoU/issues/146)

#### Enhancements:

- Refactoring - break down SharpMonoInjector into a separate repo as a submodule enhancement  [#148](https://github.com/Lady-Binary/EasyLoU/issues/148)
- Improve README and instructions [#145](https://github.com/Lady-Binary/EasyLoU/issues/145)
- Automatically reload a script from disk if it has been changed by another application [#144](https://github.com/Lady-Binary/EasyLoU/issues/144)

---

## LoA 1.4.0.0 - EasyLOU 1.2.0.1 (11/01/2021)

#### Bugfixes:

- LoU engine improperly logging command parameters to player.log [#143](https://github.com/Lady-Binary/EasyLoU/issues/143)

#### Enhancements:

- Increase default speed of client status updates [#141](https://github.com/Lady-Binary/EasyLoU/issues/141)
- New SetSpeed() command to make scripts update status more quickly. [#139](https://github.com/Lady-Binary/EasyLoU/issues/139)
- New hotkey capabilities: RegisterHotKey(), OnHotKey(), IsHotKeyDown() [#126](https://github.com/Lady-Binary/EasyLoU/issues/126)

---

## LoA 1.4.0.0 - EasyLOU 1.2.0.0 (17/12/2020)

#### Enhancements:

- Refactoring - rename master branch to main [#135](https://github.com/Lady-Binary/EasyLoU/issues/135)
- Refactoring - break down LOU.dll into a separate repo as a submodule [#132](https://github.com/Lady-Binary/EasyLoU/issues/132)
- Refactoring - rename EasyLOU to EasyLoU, LOU to LoU [#131](https://github.com/Lady-Binary/EasyLoU/issues/131)

---

## LoA 1.4.0.0 - EasyLOU 1.1.0.8 (16/12/2020)

#### Enhancements:

- New ClosePanel() command [#128](https://github.com/Lady-Binary/EasyLOU/issues/128)

---

## LoA 1.3.0.0 - EasyLOU 1.1.0.7 (07/12/2020)

#### Bugfixes:

- EasyLOU losing connection to client after Logout() command is executed [#120](https://github.com/Lady-Binary/EasyLOU/issues/120)
- Client Disconnected after using Recall [#119](https://github.com/Lady-Binary/EasyLOU/issues/119)

---

## LoA 1.3.0.0 - EasyLOU 1.1.0.6 (09/11/2020)

#### Bugfixes:

- CHARBUFFS variable inaccessible in scripts [#117](https://github.com/Lady-Binary/EasyLOU/issues/117)
- FindItem/FindPermanent/FindMobile by id not working anymore [#116](https://github.com/Lady-Binary/EasyLOU/issues/116)

---

## LoA 1.3.0.0 - EasyLOU 1.1.0.5 (03/11/2020)

#### Bugfixes:

- FindButton(), FindInput(), and FindLabel() should return all items if only the panel name is passed as an argument [#115](https://github.com/Lady-Binary/EasyLOU/issues/115)
- Unable to find Text Entry boxes reliably for SetInput() [#113](https://github.com/Lady-Binary/EasyLOU/issues/113)
- NEARBYMONSTERS/CLICKOBJ unable to access variables [#112](https://github.com/Lady-Binary/EasyLOU/issues/112)
- FindItem not clearing previously found objects/table(s) no longer on screen or in pack [#93](https://github.com/Lady-Binary/EasyLOU/issues/93)

---

## LoA 1.3.0.0 - EasyLOU 1.1.0.4 (13/10/2020)

#### Enhancements:

- Always On Top [#107](https://github.com/Lady-Binary/EasyLOU/issues/107)

---

## LoA 1.2.0.0 - EasyLOU 1.1.0.3 (12/10/2020)

#### Enhancements:

- LogOff command [#108](https://github.com/Lady-Binary/EasyLOU/issues/108)

#### function (placeholders) {
			return '';
        }

- Say() doesn't allow custom commands [#109](https://github.com/Lady-Binary/EasyLOU/issues/109)

---

## LoA 1.0.0.4 - EasyLOU 1.1.0.2 (22/08/2020)

#### Bugfixes:

- FindPermanent() makes LOU dll unresponsive and EasyLOU disconnects from the client in presence of perma objects with no texture [#104](https://github.com/Lady-Binary/EasyLOU/issues/104)

---

## LoA 1.0.0.4 - EasyLOU 1.1.0.1 (21/08/2020)

#### Bugfixes:

- Update examples with new var names [#102](https://github.com/Lady-Binary/EasyLOU/issues/102)

#### Enhancements:

- Create variables that can be shared between different scripts and EasyLOU instances, via SetVar(name, value) and ClearVar(name)  [#97](https://github.com/Lady-Binary/EasyLOU/issues/97)
- Add CHARBUFFS variable that lists buffs, hunger, poison, etc. [#92](https://github.com/Lady-Binary/EasyLOU/issues/92)

---

## LoA 1.0.0.4 - EasyLOU 1.1.0.0 (20/08/2020)

#### Bugfixes:

- All variables must be strong typed, and not just strings. Use "nil" instead of N/A. [#91](https://github.com/Lady-Binary/EasyLOU/issues/91)

#### Enhancements:

- New TreeState, RockState, and Hue attributes for permanent objects [#101](https://github.com/Lady-Binary/EasyLOU/issues/101)
- Add X,Y,Z attributes to FINDMOBILEs [#99](https://github.com/Lady-Binary/EasyLOU/issues/99)
- Add X,Y,Z attributes to FINDPERMANENTs. Add ability to use Move() with PERMANENTID. [#90](https://github.com/Lady-Binary/EasyLOU/issues/90)
- Add X,Y,Z and DISTANCE attributes to FINDITEMs (DISTANCE only for those on the ground) [#100](https://github.com/Lady-Binary/EasyLOU/issues/100)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.33 (15/08/2020)

#### Bugfixes:

- right-click contextmenu on GUI not working on FIND variables [#95](https://github.com/Lady-Binary/EasyLOU/issues/95)
- object names do not refresh when unidentified objects get identified [#94](https://github.com/Lady-Binary/EasyLOU/issues/94)
- click and mouseover variables not working with objects in containers [#87](https://github.com/Lady-Binary/EasyLOU/issues/87)

#### Enhancements:

- retrieve permanent objects (e.g. trees and rocks) textures and colors [#89](https://github.com/Lady-Binary/EasyLOU/issues/89)
- add command to clear variables stored clearVar() [#88](https://github.com/Lady-Binary/EasyLOU/issues/88)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.32 (05/08/2020)

#### Bugfixes:

- Prompt user for confirmation on main app close to save files [#85](https://github.com/Lady-Binary/EasyLOU/issues/85)

#### Enhancements:

- create hotkey for start, stop, stopall [#80](https://github.com/Lady-Binary/EasyLOU/issues/80)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.31 (04/08/2020)

#### Bugfixes:

- WaitForTarget() should wait until the cursor finished loading [#83](https://github.com/Lady-Binary/EasyLOU/issues/83)
- syntax highlight for WaitForTarget() not working [#82](https://github.com/Lady-Binary/EasyLOU/issues/82)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.30 (04/08/2020)

#### Bugfixes:

- Commands.MD missing GetTooltip from table of contents [#72](https://github.com/Lady-Binary/EasyLOU/issues/72)
- Client disconnects after char selection [#69](https://github.com/Lady-Binary/EasyLOU/issues/69)
- Align examples and public scripts with the new FIND variables [#65](https://github.com/Lady-Binary/EasyLOU/issues/65)

#### Enhancements:

- New write() command that prints to output log without newline [#74](https://github.com/Lady-Binary/EasyLOU/issues/74)
- New clear() command to clear EasyLOU output log [#68](https://github.com/Lady-Binary/EasyLOU/issues/68)
- WaitForTarget() command [#67](https://github.com/Lady-Binary/EasyLOU/issues/67)
- Add button to open the folder where Player.log can be found [#53](https://github.com/Lady-Binary/EasyLOU/issues/53)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.29 (31/07/2020)

#### Bugfixes:

- Upon disconnection, too many popup messages are displayed [#60](https://github.com/Lady-Binary/EasyLOU/issues/60)
- ClickButton doesn't work with the Sell buttons of vendors UIs [#54](https://github.com/Lady-Binary/EasyLOU/issues/54)

#### Enhancements:

- Improve FIND variables, they should be arrays/tables so that it's much easier to use them [#52](https://github.com/Lady-Binary/EasyLOU/issues/52)
- Add button to open the folder where Player.log can be found [#53](https://github.com/Lady-Binary/EasyLOU/issues/53)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.28 (30/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.27 (30/07/2020)

#### Enhancements:

- Add CHANGELOG [#58](https://github.com/Lady-Binary/EasyLOU/issues/58)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.26 (29/07/2020)

#### Enhancements:

- Add release notes to releases [#51](https://github.com/Lady-Binary/EasyLOU/issues/51)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.25 (29/07/2020)

#### Enhancements:

- Move documentation to Wiki [#50](https://github.com/Lady-Binary/EasyLOU/issues/50)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.24 (29/07/2020)

#### Enhancements:

- Display a message when EasyLOU is not connected to a client [#49](https://github.com/Lady-Binary/EasyLOU/issues/49)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.23 (28/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.22 (28/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.21 (27/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.20 (27/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.19 (27/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.18 (25/07/2020)

#### Enhancements:

- Create a ContextMenu() or ItemOption() command [#46](https://github.com/Lady-Binary/EasyLOU/issues/46)

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.17 (23/07/2020)
*No changelog for this release.*

---

## LoA 1.0.0.4 - EasyLOU 1.0.0.16 (23/07/2020)

#### Enhancements:

- HUNGER variable [#41](https://github.com/Lady-Binary/EasyLOU/issues/41)
