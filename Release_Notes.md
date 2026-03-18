---
pagetitle: Release Notes for ASM330LHHX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for ASM330LHHX Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the ASM330LHHX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section8" checked aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V2.4.0 / 18-Mar-2026</label>
<div>

## Main changes

- Fix some MISRA issues
- Add parameter names to stmdev callbacks to fix a MISRA issue
- Add const qualifier to mag_soft_iron_set API
- Remove declaration of unimplemented ln_pg_read API
- Fix hp_slope_xl_en_t LP_ODR_DIV_4 hex value
- Remove outdated incorrect comment
- Update sh_read_data_raw_get API to use a raw uint8_t buffer
- Update fsm_out_get API to read raw uint8_t buffer.
- Fix xl_hp_path_on_out_set/get API and hp_slope_xl_en_t enum
- Change switch cases to use hex values
- Re-order update history with most updated on top
- Fix style
- Change fsm_out_get return type
- Fix den_xl_g_t values
- Fix odr_t_batch_t values
- Remove register union
- Rename variants for shub_pu_en_t enum
- Fix emb_fsm_en_get, remove useless write
- Fix mag_soft_iron_set
- Fix den_mark_axis_x/z_set_get APIs
- Rename filter_settling_mask_set/get in drdy_mask_set/get
- Fix odr_cal_reg_set/get API, change type uint8 to int8
- Change type of xl_usr_offset_x/y/z_set/get APIs uint8 to int8
- Move MLC_STATUS read to MLC_STATUS_MAINPAGE in all_sources_get API
- Fix xl/gy_data_rate_set APIs

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V2.3.0 / 07-Oct-2025</label>
<div>

## Main changes

- Aligned ln_pg_write/read implementations
- Added checks before writes and membank setting
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.2.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.1.0 / 18-Dec-2024</label>
<div>

## Main changes

- Read always both FIFO_STATUS1 and FIFO_STATUS2 regs
- Align asm330lh software compatible drivers

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.0.1 / 19-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.0.0 / 19-Mar-2024</label>
<div>

## Main changes

- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.1.1 / 01-June-2023</label>
<div>

## Main changes

- Fix release_notes.md typos

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.1.0 / 08-Mar-2023</label>
<div>

## Main changes

- Fix README.md file formatting
- Aligned to DS v7.0 (23-Feb-2023)

##

</div>

<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v3.0]

##

</div>

:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on ASM330LHHX,
visit:
[ASM330LHHX](https://www.st.com/en/mems-and-sensors/asm330lhhx.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
