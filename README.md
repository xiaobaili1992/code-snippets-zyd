## 该插件主要用于提升编码效率
## 主要包含项目中常用的snippets, js、vue、element-ui、zyd-design、zyd-charts

## js 包含常用的js语法，规则如下：
* 多个单词，取每个单词的首字母，区分大小写，eg：console.log取cl；Object.entries取Oe；
* 多个单词，取每个单词的首字母，如果第二个单词首字母有重复的，继续取，eg：Math.abs取Ma；Math.acos取Mac；Math.acosh取Maco；
* 小驼峰，取驼峰前后的首字母，不区分大小写，eg：console.countReset取ccr；
* .(点)运算符，全拼，eg：.concat取.concat；

|   Snippet   | Renders                                   |
|   -------   | ----------------------------------------- |
|    `cl`     | console.log                               |
|    `Ok`     | Object.keys                               |
|    `Oe`     | Object.entries                            |
|    `Nif`    | Number.isFinite                           |
|    `ccr`    | console.countReset                        |
|   `.map`    | .map                                      |
| `.forEach`  | .forEach                                  |
| `.toFixed`  | .toFixed                                  |
|    `Ma`     | Math.abs                                  |
|    `Mac`    | Math.acos                                 |
|    `Maco`   | Math.acosh                                |
|    `Mas`    | Math.asin                                 |
|    `Masi`   | Math.asinh                                |
|    `Mat`    | Math.atan                                 |
|    `Mat2`   | Math.atan2                                |
|    `Math`   | Math.atanh                                |
|    `Mc`     | Math.cbrt                                 |
|    `Mce`    | Math.ceil                                 |
|    `Mcl`    | Math.clz32                                |
|    `Mco`    | Math.cosh                                 |
|    `Mcos`   | Math.cos                                  |
|    `Mex`    | Math.exp                                  |
|    `Mex1`   | Math.expm1                                |
|    `Ml`     | Math.log                                  |
|    `Ml10`   | Math.log10                                |
|    `Ml1p`   | Math.log1p                                |
|    `Ml2`    | Math.log2                                 |
|    `Mma`    | Math.max                                  |
|    `Mmi`    | Math.min                                  |
|    `Mr`     | Math.random                               |
|    `Mro`    | Math.round                                |
|    `Ms`     | Math.sinh                                 |
|    `Msi`    | Math.sin                                  |
|    `Msig`   | Math.sign                                 |
|    `Mt`     | Math.tan                                  |
|    `Mta`    | Math.tanh                                 |
|    `Mtr`    | Math.trunc                                |
|    `cla`    | class XXX{}                               |
|    `clae`   | class XXX extends  YYY {}                 |
|    `ex`     | export XXX                                |
|    `exp`    | export {}                                 |
|    `ed`     | export default XXX                        |
|    `ef`     | export XXX from YYY                       |
|    `i`      | import XXX                                |
|    `imf`    | import XXX from YYYY                      |
|    `impf`   | import { XXX } from YYYY                  |
|    `impof`  | import * as XXX from YYYY                 |
|    `impt`   | import(XXX).then()                        |
|    `r`      | return XXX                                |
|    `rn`     | return null                               |
|    `rt`     | return true                               |
|    `rf`     | return false                              |
|    `rth`    | return this                               |
|    `tc`     | try {} catch() {}                         |
|    `tf`     | try {} finally {}                         |
|    `tcf`    | try {} catch() {} finally {}              |
|    `v`      | var XXX                                   |
|    `var`    | var XXX = YYY                             |
|    `l`      | let XXX                                   |
|    `let`    | let XXX = YYY                             |
|    `c`      | const XXX                                 |
|    `const`  | const XXX = YYY                           |
|    `to`     | XXX ? YYYY : ZZZ                          |
|    `fl`     | for (let x = y, len = z.length) {}        |
|    `fi`     | for (let x in y) {}                       |
|    `fo`     | for (const x of y) {}                     |
|    `wl`     | while () {}                               |
|    `sw`     | switch () {}                              |
|    `fn`     | function() {}                             |
|    `iife`   | ((){})()                                  |
|    `st`     | setTimeout(() => {})                      |
|    `si`     | setInterval(() => {})                     |
|    `if`     | if () {}                                  |
|    `ife`    | if () {} else {}                          |
|    `ifei`   | if () {} else if () {}                    |
|    `ifeie`  | if () {} else if () {} else {}            |
|    `el`     | else {}                                   |
|    `ei`     | else if () {}                             |

## vue template 包含常用的vue 空模板

|     Snippet     | Renders                               |
|     -------     | ------------------------------------- |
|       `vue`     | vue2 基于scss空模板                    |
|    `vue-sass`   | vue2 基于sass空模板                    |
|    `vue-less`   | vue2 基于less空模板                    |
|    `vue-pcss`   | vue2 基于postcss空模板                 |
|    `vue-styl`   | vue2 基于stylus空模板                  |
|    `vue-ts`     | vue2 基于ts空模板                      |
|    `vue-ns`     | vue2 没有样式空模板                    |
|    `vue-3`      | vue3 基于scss空模板                    |
|  `vue-3-setup`  | vue3 setup空模板                       |
| `vue-3-reactive`| vue3 reactive空模板                    |
|    `vue-3-ts`   | vue-3-ts空模板                         |
| `vue-3-ts-setup`| vue-3-ts-setup空模板                   |

## vue 包含常用的vue语法

|     Snippet     | Renders                                   |
|     -------     | ----------------------------------------- |
|     `props`     | props: {}                                 |
|   `components`  | components: {}                            |
|      `data`     | data() {}                                 |
|    `methods`    | methods: {}                               |
|    `computed`   | computed: {}                              |
|  `beforecreate` | beforecreate() {}                         |
|    `created`    | created() {}                              |
|   `beforemount` | beforemount() {}                          |
|    `mounted`    | mounted() {}                              |
|  `beforeupdate` | beforeupdate() {}                         |
|    `updated`    | updated() {}                              |
| `beforedestroy` | beforedestroy() {}                        |
|    `destroyed`  | destroyed() {}                            |
|     `watch`     | watch: {}                                 |
|    `watcher`    | watch: {}                                 |
|    `watcher`    | watch: {}                                 |
|     `vfor`      | v-for                                     |
|     `slot`      | slot                                      |

## element-ui 包含常用的组件，规则如下：
* 组件都是el-xxx-xxx，取el和后面首字母，如果第二个单词首字母有重复的，继续取，eg：el-button取elb；el-badge取elba；el-breadcrumb取elbr；el-button-group取elbg

|     Snippet     | Renders                                   |
|     -------     | ----------------------------------------- |
|    `elrow`      | el-row                                    |
|    `elcol`      | el-col                                    |
|    `elcon`      | el-container                              |
|     `elh`       | el-header                                 |
|    `elas`       | el-aside                                  |
|    `elm`        | el-main                                   |
|    `elfo`       | el-footer                                 |
|    `elb`        | el-button                                 |
|    `elbg`       | el-button-group                           |
|    `elrgb`      | el-button-group  Button                   |
|    `ell`        | el-link                                   |
|    `elr`        | el-radio                                  |
|    `elrg`       | el-radio-group                            |
|    `elrb`       | el-radio-button                           |
|    `elc`        | el-checkbox                               |
|    `elcg`       | el-checkbox-group                         |
|    `elcgb`      | el-checkbox-group button                  |
|    `elcb`       | el-checkbox-button                        |
|    `eli`        | el-input                                  |
|    `elit`       | Textarea                                  |
|    `ela`        | el-autocomplete                           |
|    `elin`       | el-input-number                           |
|    `els`        | el-select                                 |
|    `elsr`       | el-select Remote Search                   |
|    `elo`        | el-option                                 |
|    `elog`       | el-option-group                           |
|    `elca`       | el-cascader                               |
|    `elcap`      | el-cascader Panel                         |
|    `elsw`       | el-switch                                 |
|    `elsl`       | el-slider                                 |
|    `elts`       | el-time-select                            |
|    `eltsr`      | el-time-select Range                      |
|    `eltp`       | el-time-picker                            |
|    `eltpr`      | el-time-picker Range                      |
|    `eldp`       | el-date-picker                            |
|    `eldpr`      | el-date-picker Range                      |
|    `eldtp`      | DateTimePicker                            |
|    `eldtpr`     | DateTimePicker Range                      |
|    `elu`        | el-upload                                 |
|    `elra`       | el-rate                                   |
|    `elcp`       | el-color-picker                           |
|    `eltr`       | el-transfer                               |
|    `elf`        | el-form                                   |
|    `elfi`       | el-form-item                              |
|    `elt`        | el-table                                  |
|    `eltc`       | el-table-column                           |
|    `elta`       | el-tag                                    |
|    `elpr`       | el-progress                               |
|    `eltree`     | el-tree                                   |
|    `elp`        | el-pagination                             |
|    `elba`       | el-badge                                  |
|    `elav`       | el-avatar                                 |
|    `elal`       | el-alert                                  |
|    `elmen`      | el-menu                                   |
|    `elsu`       | el-submenu                                |
|    `elmeni`     | el-menu-item                              |
|    `eltab`      | el-tabs                                   |
|    `eltabp`     | el-tab-pane                               |
|    `elbr`       | el-breadcrumb                             |
|    `elbri`      | el-breadcrumb-item                        |
|    `elph`       | el-page-header                            |
|    `eldr`       | el-dropdown                               |
|    `eldri`      | const XXX = YYY                           |
|    `elsts`      | el-steps                                  |
|    `elst`       | el-step                                   |
|    `eldi`       | el-dialog                                 |
|    `elto`       | el-tooltip                                |
|    `elpo`       | el-popover                                |
|    `elcard`     | el-card                                   |
|    `elcar`      | el-carousel                               |
|    `elcaro`     | el-carousel-item                          |
|    `elcoll`     | el-collapse                               |
|    `elcolli`    | el-collapse-item                          |
|    `elti`       | el-timeline                               |
|    `eltii`      | el-timeline-item                          |
|    `eld`        | el-divider                                |
|    `elcal`      | el-calendar                               |
|    `elim`       | el-image                                  |
|    `elback`     | el-backtop                                |
|    `eldra`      | el-drawer                                 |

## zyd-design 包含常用的组件，规则如下：
* 组件都是大驼峰格式，取大驼峰的首字母，eg：ZydLargeScreenScale取zlss

|   Snippet   | Renders                                   |
|   -------   | ----------------------------------------- |
|    `zlss`   | ZydLargeScreenScale                       |
|    `zltt`   | ZydLongTextTooltip                        |
|    `zob`    | ZydOperateBtn                             |
|    `zobc`   | ZydOperateBtn operateBtnConfig            |
|    `zt`     | ZydTag                                    |
|    `zsp`    | ZydSplitPane                              |
