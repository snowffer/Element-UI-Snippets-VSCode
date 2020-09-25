## This is Code Snippets of Element UI for VS Code.

### Install

#### Manual Install
Go to the [git](https://github.com/snowffer/Element-UI-Snippets-VSCode) and download the snippets folder, then copy the files in the folder to the path directly:

+ **Mac**: /Users/*< your-user-name >*/Library/Application Support/Code/User/snippets/
+ **Windows**: *< your-installed-driver >* :\Users\ *< your-user-name >* \AppData\Roaming\Code\User\snippets\

#### Through VS Code Extensions

+ From website: Go to Visual Studio Code [Marketplace](https://marketplace.visualstudio.com/vscode), and search 'Element UI Snippets', then click the install button.
+ From VS Code: click extensions sidebar, and search 'Element UI Snippets', then click the install button.

### Special Instruction：

1. For the components like `el-table` which need children components to be its content, use `v-for` to loop to generate the children components.

### Snippets List

1. All the Element UI tags below, ignore the closure and more detailed information. Such as `elr` to `<el-radio>`, actually that represents `<el-radio v-model="${1}" label="${2}">$3</el-radio>`
2. The sinppets' order follows the order of the components of Guide on Element UI official website basically. <!--Supply extra General and Options parts.-->
3. Totally 71 snippets. Will add more if necessary.
4. **Only work in .vue file for now.**



#### Basic Part
|No.|Trigger&nbsp;Key|Element Tag|
|:------:|:--------------:|:--------|
|1. | `elrow` | `<el-row>` |
|2. | `elcol` | `<el-col>` |
|3. | `elcon` | `<el-container>` |
|4. | `elas` | `<el-aside>` |
|5. | `elhe` | `<el-header>` |
|6. | `elma` | `<el-main>` |
|7. | `elfo` | `<el-footer>` |
|8. | `elcb` | `#409EFF` |
|9. | `elcs` | `#67C23A` |
|10. | `elcw` | `#E6A23C` |
|11. | `elcd` | `#F56C6C` |
|12. | `elci` | `#909399` |
|13. | `eltypo` | `font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;` |
|14. | `elb` | `el-button` |


#### Form Part

|No. |  Trigger&nbsp;Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elr` | `<el-radio>` |
|2. | `elrg` | `<el-radio-group>` |
|3. | `elc` | `<el-checkbox>` |
|4. | `elcg` | `<el-checkbox-group>` |
|5. | `eli` | `<el-input>` |
|6. | `elit` | `<el-input type="textarea">` |
|7. | `elin` | `<el-input-number>` |
|8. | `elsel` | `<el-select>` |
|9. | `elop` | `<el-option>` |
|10. | `elca` | `<el-cascader>` |
|11. | `elsw` | `<el-swtich>` |
|12. | `elsl` | `<el-slider>` |
|13. | `eltp` | `<el-time-picker>` |
|14. | `elts` | `<el-time-select>` |
|15. | `eldp` | `<el-date-picker>` |
|16. | `eldtp` | `<el-date-picker type="datetime">` |
|17. | `elu` | `<el-upload>` |
|18. | `elra` | `<el-rate>` |
|19. | `elcp` | `<el-color-picker>` |
|20. | `eltr` | `<el-transfer>` |
|21. | `elf` | `<el-form>` |
|22. | `elfi` | `<el-form-item>` |


#### Data Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elta` | `<el-table>` |
|2. | `eltac` | `<el-table-column>` |
|3. | `eltag` | `<el-tag>` |
|4. | `elpr` | `<el-progress>` |
|5. | `elprc` | `<el-progress type="circle">` |
|6. | `eltree` | `<el-tree>` |
|7. | `elpa` | `<el-pagination>` |
|8. | `elba` | `<el-badge>` |


#### Notice Part

|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elal` | `<el-alert>` |
|2. | `elloads` | 	`element-loading-*` |
|3. | `elme` | 	`this.$message({})` |
|4. | `elmebox` | 	`this.$msgbox({})` |
|5. | `elmeal` | 	`this.$alert({})` |
|6. | `elmecon` | 	`this.$confirm({})` |
|7. | `elmepro` | 	`this.$prompt({})` |
|8. | `elnoti` | 	`this.$notify({})` |



#### Navigation Part
|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `elmen` | `<el-menu>` |
|2. | `elsubmen` | `<el-submenu>` |
|3. | `elmeni` | `<el-menu-item>` |
|4. | `eltabs` | `<el-tabs>` |
|5. | `eltabp` | `<el-tab-pane>` |
|6. | `elbr` | `<el-breadcrumb>` |
|7. | `elbri` | `<el-breadcrumb-item>` |
|8. | `eldr` | `<el-dropdown>` |
|9. | `eldri` | `<el-dropdown-item>` |
|10. | `elsts` | `<el-steps>` |
|11. | `elst` | `<el-step>` |

#### Others Part
|No. |  Trigger Key | Element Tag|
|:------:|:--------------:|:--------|
|1. | `eldi` | `<el-dialog>` |
|2. | `elto` | `<el-tooltip>` |
|3. | `elpop` | `<el-popover>` |
|4. | `elcard` | `<el-card>` |
|5. | `elcaro` | `<el-carousel>` |
|6. | `elcaroi` | `<el-carousel-item>` |
|7. | `elcolla` | `<el-collapse>` |
|8. | `elcollai` | `<el-collapse-item>` |

<!--
#### General Part
No. |  Trigger Key | Element Tag
|:------:|:--------------:|:--------|
|1. | `el` | `<el-*>` |
|2. | `elic` | `<el-icon-*>` |

#### Options Part
No. |  Trigger Key | Element Tag
|:------:|:--------------:|:--------|
|1. | `elpos` | positions |
|2. | `elanims` | animation types |
-->
<!--
#### #TODO
1. `tree`的data值
2. `import`样式的快捷方式
3. 不同类型的`button`
4. 各种引用路径：内置动画，样式
-->


