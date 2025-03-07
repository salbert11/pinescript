*Version 3.4.2*
# Snippet's Prefix's

- [Snippet's Prefix's](#snippets-prefixs)
  - [Built-In\_Variables](#built-in_variables)
  - [Built-In\_Functions](#built-in_functions)
  - [Built-In\_Constants](#built-in_constants)
  - [Built-In\_Scripts](#built-in_scripts)
  - [Operators](#operators)
  - [Keywords](#keywords)
  - [Comments](#comments)
  - [Added\_Functions\_|\_scripts](#added_functions__scripts)
  - [Unicode](#unicode)
  - [Parameters\_|\_Words](#parameters__words)
  - [Extra](#extra)

## Built-In_Variables

|                                   |
|               ---                 |
|`bar_index`                        |
|`barstate.isconfirmed`             |
|`barstate.isfirst`                 |
|`barstate.ishistory`               |
|`barstate.islast`                  |
|`barstate.islastconfirmedhistory`  |
|`barstate.isnew`                   |
|`barstate.isrealtime`              |
|`box.all`                          |
|`chart.bg_color`                   |
|`chart.fg_color`                   |
|`chart.is_heikinashi`              |
|`chart.is_kagi`                    |
|`chart.is_linebreak`               |
|`chart.is_pnf`                     |
|`chart.is_range`                   |
|`chart.is_renko`                   |
|`chart.is_standard`                |
|`chart.left_visible_bar_time`      |
|`chart.right_visible_bar_time`     |
|`close`                            |
|`dayofmonth`                       |
|`dayofweek`                        |
|`dividends.future_amount`          |
|`dividends.future_ex_date`         |
|`dividends.future_pay_date`        |
|`earnings.future_eps`              |
|`earnings.future_period_end_time`  |
|`earnings.future_revenue`          |
|`earnings.future_time`             |
|`high`                             |
|`hl2`                              |
|`hlc3`                             |
|`hlcc4`                            |
|`hour`                             |
|`label.all`                        |
|`last_bar_index`                   |
|`last_bar_time`                    |
|`line.all`                         |
|`linefill.all`                     |
|`low`                              |
|`minute`                           |
|`month`                            |
|`na`                               |
|`ohlc4`                            |
|`open`                             |
|`polyline.all`                     |
|`second`                           |
|`session.isfirstbar`               |
|`session.isfirstbar_regular`       |
|`session.islastbar`                |
|`session.islastbar_regular`        |
|`session.ismarket`                 |
|`session.ispostmarket`             |
|`session.ispremarket`              |
|`strategy.account_currency`        |
|`strategy.avg_losing_trade`        |
|`strategy.avg_losing_trade_percent`|
|`strategy.avg_trade`               |
|`strategy.avg_trade_percent`       |
|`strategy.avg_winning_trade`       |
|`strategy.avg_winning_trade_percent`|
|`strategy.closedtrades`            |
|`strategy.equity`                  |
|`strategy.eventrades`              |
|`strategy.grossloss`               |
|`strategy.grossprofit`             |
|`strategy.grossloss_percent`       |
|`strategy.grossprofit_percent`     |
|`strategy.initial_capital`         |
|`strategy.long`                    |
|`strategy.losstrades`              |
|`strategy.margin_liquidation_price`|
|`strategy.max_contracts_held_all`  |
|`strategy.max_contracts_held_long` |
|`strategy.max_contracts_held_short`|
|`strategy.max_drawdown`            |
|`strategy.max_runup`               |
|`strategy.netprofit`               |
|`strategy.openprofit`              |
|`strategy.max_drawdown_percent`    |
|`strategy.max_runup_percent`       |
|`strategy.netprofit_percent`       |
|`strategy.openprofit_percent`      |
|`strategy.opentrades`              |
|`strategy.opentrades.capital_held` |
|`strategy.position_avg_price`      |
|`strategy.position_entry_name`     |
|`strategy.position_size`           |
|`strategy.short`                   |
|`strategy.wintrades`               |
|`syminfo.basecurrency`             |
|`syminfo.country`                  |
|`syminfo.currency`                 |
|`syminfo.description`              |
|`syminfo.employees`                |
|`syminfo.expiration_date`          |
|`syminfo.industry`                 |
|`syminfo.minmove`                  |
|`syminfo.mintick`                  |
|`syminfo.pointvalue`               |
|`syminfo.prefix`                   |
|`syminfo.pricescale`               |
|`syminfo.recommendations_buy`      |
|`syminfo.recommendations_buy_strong`|
|`syminfo.recommendations_date`     |
|`syminfo.recommendations_hold`     |
|`syminfo.recommendations_sell`     |
|`syminfo.recommendations_sell_strong`|
|`syminfo.recommendations_total`    |
|`syminfo.root`                     |
|`syminfo.sector`                   |
|`syminfo.session`                  |
|`syminfo.shareholders`             |
|`syminfo.shares_outstanding_float` |
|`syminfo.shares_outstanding_total` |
|`syminfo.target_price_average`     |
|`syminfo.target_price_date`        |
|`syminfo.target_price_estimates`   |
|`syminfo.target_price_high`        |
|`syminfo.target_price_low`         |
|`syminfo.target_price_median`      |
|`syminfo.ticker`                   |
|`syminfo.tickerid`                 |
|`syminfo.timezone`                 |
|`syminfo.type`                     |
|`syminfo.volumetype`               |
|`ta.accdist`                       |
|`ta.iii`                           |
|`ta.nvi`                           |
|`ta.obv`                           |
|`ta.pvi`                           |
|`ta.pvt`                           |
|`ta.tr`                            |
|`ta.vwap`                          |
|`ta.wad`                           |
|`ta.wvad`                          |
|`table.all`                        |
|`time`                             |
|`time_close`                       |
|`time_tradingday`                  |
|`timeframe.isdaily`                |
|`timeframe.isdwm`                  |
|`timeframe.isintraday`             |
|`timeframe.isminutes`              |
|`timeframe.ismonthly`              |
|`timeframe.isseconds`              |
|`timeframe.isticks` _**new!**_                                          |
|`timeframe.isweekly`               |
|`timeframe.multiplier`             |
|`timeframe.period`                 |
|`timenow`                          |
|`volume`                           |
|`weekofyear`                       |
|`year`                             |

-----

## Built-In_Functions
|                                          |
|                   ---                    |
|`alert`                                   |
|`alertcondition`                          |
|`array.abs`                               |
|`array.avg`                               |
|`array.binary_search`                     |
|`array.binary_search_leftmost`            |
|`array.binary_search_rightmost`           |
|`array.clear`                             |
|`array.concat`                            |
|`array.copy`                              |
|`array.covariance`                        |
|`array.every`                             |
|`array.fill`                              |
|`array.first`                             |
|`array.from`                              |
|`array.get`                               |
|`array.includes`                          |
|`array.indexof`                           |
|`array.insert`                            |
|`array.join`                              |
|`array.last`                              |
|`array.lastindexof`                       |
|`array.max`                               |
|`array.median`                            |
|`array.min`                               |
|`array.mode`                              |
|`array.new_bool`                          |
|`array.new_box`                           |
|`array.new_color`                         |
|`array.new_float`                         |
|`array.new_int`                           |
|`array.new_label`                         |
|`array.new_line`                          |
|`array.new_linefill`                      |
|`array.new_string`                        |
|`array.new_table`                         |
|`array.new`                               |
|`array.percentile_linear_interpolation`   |
|`array.percentile_nearest_rank`           |
|`array.percentrank`                       |
|`array.pop`                               |
|`array.push`                              |
|`array.range`                             |
|`array.remove`                            |
|`array.reverse`                           |
|`array.set`                               |
|`array.shift`                             |
|`array.size`                              |
|`array.slice`                             |
|`array.some`                              |
|`array.sort`                              |
|`array.sort_indices`                      |
|`array.standardize`                       |
|`array.stdev`                             |
|`array.sum`                               |
|`array.unshift`                           |
|`array.variance`                          |
|`matrix.add_col`                          |
|`matrix.add_row`                          |
|`matrix.avg`                              |
|`matrix.col`                              |
|`matrix.columns`                          |
|`matrix.concat`                           |
|`matrix.copy`                             |
|`matrix.det`                              |
|`matrix.diff`                             |
|`matrix.eigenvalues`                      |
|`matrix.eigenvectors`                     |
|`matrix.elements_count`                   |
|`matrix.fill`                             |
|`matrix.get`                              |
|`matrix.inv`                              |
|`matrix.is_antidiagonal`                  |
|`matrix.is_antisymmetric`                 |
|`matrix.is_binary`                        |
|`matrix.is_diagonal`                      |
|`matrix.is_identity`                      |
|`matrix.is_square`                        |
|`matrix.is_stochastic`                    |
|`matrix.is_symmetric`                     |
|`matrix.is_triangular`                    |
|`matrix.is_zero`                          |
|`matrix.kron`                             |
|`matrix.max`                              |
|`matrix.median`                           |
|`matrix.min`                              |
|`matrix.mode`                             |
|`matrix.mult`                             |
|`matrix.pinv`                             |
|`matrix.pow`                              |
|`matrix.rank`                             |
|`matrix.remove_col`                       |
|`matrix.remove_row`                       |
|`matrix.reshape`                          |
|`matrix.reverse`                          |
|`matrix.row`                              |
|`matrix.rows`                             |
|`matrix.set`                              |
|`matrix.sort`                             |
|`matrix.submatrix`                        |
|`matrix.sum`                              |
|`matrix.swap_columns`                     |
|`matrix.swap_rows`                        |
|`matrix.trace`                            |
|`matrix.transpose`                        |
|`matrix.new`                              |
|`barcolor`                                |
|`bgcolor`                                 |
|`bool`                                    |
|`box`                                     |
|`box.copy`                                |
|`box.delete`                              |
|`box.get_bottom`                          |
|`box.get_left`                            |
|`box.get_right`                           |
|`box.get_top`                             |
|`box.new.block`                           |
|`box.new`                                 |
|`box.new.point`                           |
|`box.set_bgcolor`                         |
|`box.set_border_color`                    |
|`box.set_border_style`                    |
|`box.set_border_width`                    |
|`box.set_bottom`                          |
|`box.set_bottom_right_point`              |
|`box.set_extend`                          |
|`box.set_left`                            |
|`box.set_lefttop`                         |
|`box.set_right`                           |
|`box.set_rightbottom`                     |
|`box.set_text`                            |
|`box.set_text_color`                      |
|`box.set_text_font_family`                |
|`box.set_text_halign`                     |
|`box.set_text_size`                       |
|`box.set_text_valign`                     |
|`box.set_text_wrap`                       |
|`box.set_top`                             |
|`box.set_top_left_point`                  |
|`chart.point.copy`                        |
|`chart.point.from_index`                  |
|`chart.point.from_time`                   |
|`chart.point.new`                         |
|`chart.point.now`                         |
|`color.b`                                 |
|`color.from_gradient`                     |
|`color.g`                                 |
|`color.new`                               |
|`color.r`                                 |
|`color.rgb`                               |
|`color.t`                                 |
|`dayofmonth`                              |
|`dayofweek`                               |
|`fill.hline`                              |
|`fill.plot`                               |
|`fixnan`                                  |
|`float`                                   |
|`hline`                                   |
|`hour`                                    |
|`input`                                   |
|`input.bool`                              |
|`input.color`                             |
|`input.enum`                              |
|`input.float`                             |
|`input.float.options`                     |
|`input.int`                               |
|`input.int.options`                       |
|`input.price`                             |
|`input.session`                           |
|`input.source`                            |
|`input.string`                            |
|`input.symbol`                            |
|`input.text_area`                         |
|`input.time`                              |
|`input.timeframe`                         |
|`int`                                     |
|`label`                                   |
|`label.copy`                              |
|`label.delete`                            |
|`label.get_text`                          |
|`label.get_x`                             |
|`label.get_y`                             |
|`label.new`                               |
|`label.new.block`                         |
|`label.set_color`                         |
|`label.set_size`                          |
|`label.set_style`                         |
|`label.set_text`                          |
|`label.set_text_font_family`              |
|`label.set_textalign`                     |
|`label.set_textcolor`                     |
|`label.set_tooltip`                       |
|`label.set_x`                             |
|`label.set_xloc`                          |
|`label.set_xy`                            |
|`label.set_y`                             |
|`label.set_yloc`                          |
|`line`                                    |
|`library`                                 |
|`line.copy`                               |
|`line.delete`                             |
|`line.get_price`                          |
|`line.get_x1`                             |
|`line.get_x2`                             |
|`line.get_y1`                             |
|`line.get_y2`                             |
|`line.new`                                |
|`line.set_color`                          |
|`line.set_extend`                         |
|`line.set_first_point`                    |
|`line.set_second_point`                   |
|`line.set_style`                          |
|`line.set_width`                          |
|`line.set_x1`                             |
|`line.set_x2`                             |
|`line.set_xloc`                           |
|`line.set_xy1`                            |
|`line.set_xy2`                            |
|`line.set_y1`                             |
|`line.set_y2`                             |
|`linefill`                                |
|`linefill.delete`                         |
|`linefill.get_line1`                      |
|`linefill.get_line2`                      |
|`linefill.new`                            |
|`log.error`                               |
|`log.info`                                |
|`log.warning`                             |
|`map.clear`                               |
|`map.contains`                            |
|`map.copy`                                |
|`map.get`                                 |
|`map.keys`                                |
|`map.new`                                 |
|`map.put`                                 |
|`map.put_all`                             |
|`map.remove`                              |
|`map.size`                                |
|`map.values`                              |
|`linefill.set_color`                      |
|`math.abs`                                |
|`math.acos`                               |
|`math.asin`                               |
|`math.atan`                               |
|`math.avg`                                |
|`math.ceil`                               |
|`math.cos`                                |
|`math.exp`                                |
|`math.floor`                              |
|`math.log`                                |
|`math.log10`                              |
|`math.max`                                |
|`math.min`                                |
|`math.pow`                                |
|`math.random`                             |
|`math.round`                              |
|`math.round_to_mintick`                   |
|`math.sign`                               |
|`math.sin`                                |
|`math.sqrt`                               |
|`math.sum`                                |
|`math.tan`                                |
|`math.todegrees`                          |
|`math.toradians`                          |
|`max_bars_back`                           |
|`minute`                                  |
|`month`                                   |
|`na`                                      |
|`nz`                                      |
|`plot`                                    |
|`plot.block`                              |
|`plotarrow`                               |
|`plotarrow.block`                         |
|`plotbar`                                 |
|`plotbar.block`                           |
|`plotcandle`                              |
|`plotcandle.block`                        |
|`plotchar.block`                          |
|`plotchar`                                |
|`plotshape.block`                         |
|`plotshape`                               |
|`polyline.delete`                         |
|`polyline.new`                            |
|`request.currency_rate`                   |
|`request.dividends`                       |
|`request.earnings`                        |
|`request.economic`                        |
|`request.financial`                       |
|`request.quandl`                          |
|`request.security`                        |
|`request.security_lower_tf`               |
|`request.seed`                            |
|`request.splits`                          |
|`runtime.error`                           |
|`second`                                  |
|`str.contains`                            |
|`str.endswith`                            |
|`str.format`                              |
|`str.format_time`                         |
|`str.length`                              |
|`str.lower`                               |
|`str.match`                               |
|`str.pos`                                 |
|`str.replace`                             |
|`str.repeat`                              |
|`str.replace_all`                         |
|`str.split`                               |
|`str.startswith`                          |
|`str.substring`                           |
|`str.tonumber`                            |
|`str.tostring`                            |
|`str.trim`                                |
|`str.upper`                               |
|`strategy.cancel`                         |
|`strategy.cancel_all`                     |
|`strategy.close`                          |
|`strategy.close_all`                      |
|`strategy.closedtrades.commission`        |
|`strategy.closedtrades.entry_bar_index`   |
|`strategy.closedtrades.entry_comment`     |
|`strategy.closedtrades.entry_id`          |
|`strategy.closedtrades.entry_price`       |
|`strategy.closedtrades.entry_time`        |
|`strategy.closedtrades.exit_bar_index`    |
|`strategy.closedtrades.exit_comment`      |
|`strategy.closedtrades.exit_id`           |
|`strategy.closedtrades.exit_price`        |
|`strategy.closedtrades.exit_time`         |
|`strategy.closedtrades.max_drawdown`      |
|`strategy.closedtrades.max_runup`         |
|`strategy.closedtrades.profit`            |
|`strategy.closedtrades.max_drawdown_percent`|
|`strategy.closedtrades.max_runup_percent` |
|`strategy.closedtrades.profit_percent`    |
|`strategy.closedtrades.size`              |
|`strategy.convert_to_account`             |
|`strategy.convert_to_symbol`              |
|`strategy.default_entry_qty`              |
|`strategy.entry`                          |
|`strategy.entry.block`                    |
|`strategy.exit`                           |
|`strategy.exit.block`                     |
|`strategy.opentrades.commission`          |
|`strategy.opentrades.entry_bar_index`     |
|`strategy.opentrades.entry_comment`       |
|`strategy.opentrades.entry_id`            |
|`strategy.opentrades.entry_price`         |
|`strategy.opentrades.entry_time`          |
|`strategy.opentrades.max_drawdown`        |
|`strategy.opentrades.max_runup`           |
|`strategy.opentrades.profit`              |
|`strategy.opentrades.max_drawdown_percent`|
|`strategy.opentrades.max_runup_percent`   |
|`strategy.opentrades.profit_percent`      |
|`strategy.opentrades.size`                |
|`strategy.order.block`                    |
|`strategy.order`                          |
|`strategy.risk.allow_entry_in`            |
|`strategy.risk.max_cons_loss_days`        |
|`strategy.risk.max_drawdown`              |
|`strategy.risk.max_intraday_filled_orders`|
|`strategy.risk.max_intraday_loss`         |
|`strategy.risk.max_position_size`         |
|`string`                                  |
|`syminfo.prefix`                          |
|`syminfo.ticker`                          |
|`ta.alma`                                 |
|`ta.atr`                                  |
|`ta.barssince`                            |
|`ta.bb`                                   |
|`ta.bbw`                                  |
|`ta.cci`                                  |
|`ta.change`                               |
|`ta.cmo`                                  |
|`ta.cog`                                  |
|`ta.correlation`                          |
|`ta.cross`                                |
|`ta.crossover`                            |
|`ta.crossunder`                           |
|`ta.cum`                                  |
|`ta.dev`                                  |
|`ta.dmi`                                  |
|`ta.ema`                                  |
|`ta.falling`                              |
|`ta.highest`                              |
|`ta.highestbars`                          |
|`ta.hma`                                  |
|`ta.kc`                                   |
|`ta.kcw`                                  |
|`ta.linreg`                               |
|`ta.lowest`                               |
|`ta.lowestbars`                           |
|`ta.macd`                                 |
|`ta.max`                                  |
|`ta.median`                               |
|`ta.mfi`                                  |
|`ta.min`                                  |
|`ta.mode`                                 |
|`ta.mom`                                  |
|`ta.percentile_linear_interpolation`      |
|`ta.percentile_nearest_rank`              |
|`ta.percentrank`                          |
|`ta.pivot_point_levels`                   |
|`ta.pivothigh`                            |
|`ta.pivotlow`                             |
|`ta.range`                                |
|`ta.rising`                               |
|`ta.rma`                                  |
|`ta.roc`                                  |
|`ta.rsi`                                  |
|`ta.sar`                                  |
|`ta.sma`                                  |
|`ta.stdev`                                |
|`ta.stoch`                                |
|`ta.supertrend`                           |
|`ta.swma`                                 |
|`ta.tr`                                   |
|`ta.tsi`                                  |
|`ta.valuewhen`                            |
|`ta.variance`                             |
|`ta.vwap`                                 |
|`ta.vwma`                                 |
|`ta.wma`                                  |
|`ta.wpr`                                  |
|`table`                                   |
|`table.cell.block`                        |
|`table.cell`                              |
|`table.cell_set_bgcolor`                  |
|`table.cell_set_height`                   |
|`table.cell_set_text`                     |
|`table.cell_set_text_color`               |
|`table.cell_set_text_font_family`         |
|`table.cell_set_text_halign`              |
|`table.cell_set_text_size`                |
|`table.cell_set_text_valign`              |
|`table.cell_set_tooltip`                  |
|`table.cell_set_width`                    |
|`table.clear`                             |
|`table.delete`                            |
|`table.new.block`                         |
|`table.new`                               |
|`table.set_bgcolor`                       |
|`table.set_border_color`                  |
|`table.set_border_width`                  |
|`table.set_frame_color`                   |
|`table.set_frame_width`                   |
|`table.set_position`                      |
|`ticker.heikinashi`                       |
|`ticker.inherit`                          |
|`ticker.kagi`                             |
|`ticker.linebreak`                        |
|`ticker.modify`                           |
|`ticker.new`                              |
|`ticker.pointfigure`                      |
|`ticker.renko`                            |
|`ticker.standard`                         |
|`time`                                    |
|`time_close`                              |
|`timeframe.change`                        |
|`timeframe.from_seconds`                  |
|`timeframe.in_seconds`                    |
|`timestamp`                               |
|`timestamp.int`                           |
|`timestamp.string.1`                      |
|`timestamp.string.2`                      |
|`timestamp.string.3`                      |
|`weekofyear`                              |
|`year`                                    |

-----

## Built-In_Constants

|                                          |
|                   ---                    |
|`adjustment.dividends`                    |
|`adjustment.none`                         |
|`adjustment.splits`                       |
|`alert.freq_all`                          |
|`alert.freq_once_per_bar`                 |
|`alert.freq_once_per_bar_close`           |
|`backadjustment.inherit` _**new!**_                                        |
|`backadjustment.off` _**new!**_                                            |
|`backadjustment.inheonrit` _**new!**_                                      |
|`barmerge.gaps_off`                       |
|`barmerge.gaps_on`                        |
|`barmerge.lookahead_off`                  |
|`barmerge.lookahead_on`                   |
|`color.aqua`                              |
|`color.black`                             |
|`color.blue`                              |
|`color.fuchsia`                           |
|`color.gray`                              |
|`color.green`                             |
|`color.lime`                              |
|`color.maroon`                            |
|`color.navy`                              |
|`color.olive`                             |
|`color.orange`                            |
|`color.purple`                            |
|`color.red`                               |
|`color.silver`                            |
|`color.teal`                              |
|`color.white`                             |
|`color.yellow`                            |
|`currency.AUD`                            |
|`currency.BTC`                            |
|`currency.CAD`                            |
|`currency.CHF`                            |
|`currency.ETH`                            |
|`currency.EUR`                            |
|`currency.GBP`                            |
|`currency.HKD`                            |
|`currency.INR`                            |
|`currency.JPY`                            |
|`currency.KRW`                            |
|`currency.MYR`                            |
|`currency.NOK`                            |
|`currency.NONE`                           |
|`currency.NZD`                            |
|`currency.RUB`                            |
|`currency.SEK`                            |
|`currency.SGD`                            |
|`currency.TRY`                            |
|`currency.USD`                            |
|`currency.USDT`                           |
|`currency.ZAR`                            |
|`dayofweek.friday`                        |
|`dayofweek.monday`                        |
|`dayofweek.saturday`                      |
|`dayofweek.sunday`                        |
|`dayofweek.thursday`                      |
|`dayofweek.tuesday`                       |
|`dayofweek.wednesday`                     |
|`display.all`                             |
|`display.data_window`                     |
|`display.none`                            |
|`display.pane`                            |
|`display.price_scale`                     |
|`display.status_line`                     |
|`dividends.gross`                         |
|`dividends.net`                           |
|`earnings.actual`                         |
|`earnings.estimate`                       |
|`earnings.standardized`                   |
|`extend.both`                             |
|`extend.left`                             |
|`extend.none`                             |
|`extend.right`                            |
|`font.family_default`                     |
|`font.family_monospace`                   |
|`format.inherit`                          |
|`format.mintick`                          |
|`format.percent`                          |
|`format.price`                            |
|`format.volume`                           |
|`hline.style_dashed`                      |
|`hline.style_dotted`                      |
|`hline.style_solid`                       |
|`label.style_arrowdown`                   |
|`label.style_arrowup`                     |
|`label.style_circle`                      |
|`label.style_cross`                       |
|`label.style_diamond`                     |
|`label.style_flag`                        |
|`label.style_label_center`                |
|`label.style_label_down`                  |
|`label.style_label_left`                  |
|`label.style_label_lower_left`            |
|`label.style_label_lower_right`           |
|`label.style_label_right`                 |
|`label.style_label_up`                    |
|`label.style_label_upper_left`            |
|`label.style_label_upper_right`           |
|`label.style_none`                        |
|`label.style_square`                      |
|`label.style_text_outline`                |
|`label.style_triangledown`                |
|`label.style_triangleup`                  |
|`label.style_xcross`                      |
|`line.style_arrow_both`                   |
|`line.style_arrow_left`                   |
|`line.style_arrow_right`                  |
|`line.style_dashed`                       |
|`line.style_dotted`                       |
|`line.style_solid`                        |
|`location.abovebar`                       |
|`location.absolute`                       |
|`location.belowbar`                       |
|`location.bottom`                         |
|`location.top`                            |
|`math.e`                                  |
|`math.phi`                                |
|`math.pi`                                 |
|`math.rphi`                               |
|`order.ascending`                         |
|`order.descending`                        |
|`plot.style_area`                         |
|`plot.style_areabr`                       |
|`plot.style_circles`                      |
|`plot.style_columns`                      |
|`plot.style_cross`                        |
|`plot.style_histogram`                    |
|`plot.style_line`                         |
|`plot.style_linebr`                       |
|`plot.style_stepline`                     |
|`plot.style_stepline_diamond`             |
|`plot.style_steplinebr`                   |
|`position.bottom_center`                  |
|`position.bottom_left`                    |
|`position.bottom_right`                   |
|`position.middle_center`                  |
|`position.middle_left`                    |
|`position.middle_right`                   |
|`position.top_center`                     |
|`position.top_left`                       |
|`position.top_right`                      |
|`scale.left`                              |
|`scale.none`                              |
|`scale.right`                             |
|`session.extended`                        |
|`session.regular`                         |
|`settlement_as_close.inherit` _**new!**_                            |
|`settlement_as_close.off` _**new!**_                                |
|`settlement_as_close.on` _**new!**_                                 |
|`shape.arrowdown`                         |
|`shape.arrowup`                           |
|`shape.circle`                            |
|`shape.cross`                             |
|`shape.diamond`                           |
|`shape.flag`                              |
|`shape.labeldown`                         |
|`shape.labelup`                           |
|`shape.square`                            |
|`shape.triangledown`                      |
|`shape.triangleup`                        |
|`shape.xcross`                            |
|`size.auto`                               |
|`size.huge`                               |
|`size.large`                              |
|`size.normal`                             |
|`size.small`                              |
|`size.tiny`                               |
|`splits.denominator`                      |
|`splits.numerator`                        |
|`strategy.cash`                           |
|`strategy.commission.cash_per_contract`   |
|`strategy.commission.cash_per_order`      |
|`strategy.commission.percent`             |
|`strategy.direction.all`                  |
|`strategy.direction.long`                 |
|`strategy.direction.short`                |
|`strategy.fixed`                          |
|`strategy.oca.cancel`                     |
|`strategy.oca.none`                       |
|`strategy.oca.reduce`                     |
|`strategy.percent_of_equity`              |
|`text.align_bottom`                       |
|`text.align_center`                       |
|`text.align_left`                         |
|`text.align_right`                        |
|`text.align_top`                          |
|`text.wrap_auto`                          |
|`text.wrap_none`                          |
|`xloc.bar_index`                          |
|`xloc.bar_time`                           |
|`yloc.abovebar`                           |
|`yloc.belowbar`                           |
|`yloc.price`                              |

-----

## Built-In_Scripts

|                                                           |
|                           ---                             |
|   `s.alma \| script.arnaud.legoux.moving.average`         |
|   `s.aroon \| script.aroon`                               |
|   `s.autofib \| script.auto.fibonnaci`                    |
|   `s.adx \| s.dmi \| script.directional.movement.index`   |
|   `s.ao \| script.awesome.oscillator`                     |
|   `s.balance.power \| script.balance.power`               |
|   `s.bb \| script.bollinger.bands`                        |
|   `s.cmf \| script.chaikin.money.flow`                    |
|   `s.co \| script.chaikin.oscillator`                     |
|   `s.cks \| script.chande.kroll.stop`                     |
|   `s.cmo \| script.chandler.momentum.oscillator`          |
|   `s.cz \| script.chop.zone`                              |
|   `s.chopindex \| script.choppiness.index`                |
|   `s.cci \| script.commodity.channel.index`               |

-----

## Operators

|              |
|     ---      |
|   `%`        |
|   `%=`       |
|   `*`        |
|   `*=`       |
|   `+`        |
|   `+=`       |
|   `-`        |
|   `-=`       |
|   `/`        |
|   `/=`       |
|   `<`        |
|   `<=`       |
|   `==`       |
|   `=>`       |
|   `>`        |
|   `>=`       |
|   `?:`       |
|   `=`        |

-----

## Keywords
|              |
|     ---      |
|   `and`      |
|   `else`     |
|   `else if`  |
|   `export`   |
|   `for`      |
|   `if`       |
|   `import`   |
|   `method`   |
|   `not`      |
|   `or`       |
|   `const`    |
|   `series`   |
|   `simple`   |
|   `switch`   |
|   `type`     |
|   `var`      |
|   `varip`    |
|   `while`    |
|   `true`     |
|   `false`    |
|   `continue` |
|   `break`    |
|   `enum`     |

-----

## Comments

|                                            |
|                    ---                     |
|   `// \| ln \| comment.line_1`             |
|   `// \| lnn \| comment.line_2`            |
|   `// \| comment.line_2`                   |
|   `// \| bx \| comment.box_1`              |
|   `bxx \| comment.big.box_1`               |
|   `// \| bx2 \| comment.box_2`             |
|   `// \| bxx2 \| comment.big.box_2`        |
|   `// \| comment.big.box_3`                |
|   `// \| bxlist \| comment.box.list`       |
|   `// \| bxlistn \| comment.box.list_num`  |
|   `// \| bxxx \| comment.box.big3`         |
|   `// \| // @description`                  |
|   `// \| // @param`                        |
|   `// \| // @function`                     |
|   `// \| // @returns`                      |

-----

## Added_Functions_|_scripts

|                     |
|         ---         |
|   `f.array.label`   |
|   `f.gradient`      |
|   `f.security`      |
|   `f.backtesting`   |
|   `f.bb`            |
|   `f.stoploss`      |

-----

## Unicode

|                     |
|         ---         |
|   `unicode.emoji`   |
|   `unicode.info`    |
|   `unicode.symbol`  |

-----

## Parameters_|_Words

|                                       |
|                  ---                  |
|   `alert_message`                     |
|   `backtest_fill_limits_assumption`   |
|   `bgcolor`                           |
|   `bordercolor`                       |
|   `calc_on_order_fills`               |
|   `char`                              |
|   `close_entries_rule`                |
|   `color`                             |
|   `comment`                           |
|   `commission_type`                   |
|   `currency`                          |
|   `default_qty_type`                  |
|   `defval`                            |
|   `display`                           |
|   `editable`                          |
|   `explicit_plot_zorder`              |
|   `export \| library.function`        |
|   `field`                             |
|   `format`                            |
|   `formatString`                      |
|   `freq =`                            |
|   `from_entry`                        |
|   `gaps`                              |
|   `group`                             |
|   `ignore_invalid_symbol`             |
|   `import`                            |
|   `inline`                            |
|   `join`                              |
|   `linestyle`                         |
|   `location`                          |
|   `lookahead`                         |
|   `message`                           |
|   `order`                             |
|   `overlay`                           |
|   `position`.                         |
|   `process_orders_on_close`.          |
|   `scale`                             |
|   `separator`                         |
|   `shorttitle`                        |
|   `size`                              |
|   `style`                             |
|   `textalign`                         |
|   `text_halign`                       |
|   `text_size`                         |
|   `text_valign`                       |
|   `ticker`                            |
|   `timeframe`                         |
|   `timezone`                          |
|   `title`                             |
|   `tooltip`                           |
|   `tooltip`                           |
|   `tooltip.text`                      |
|   `trackprice`                        |
|   `wickcolor`                         |
|   `xloc`                              |
|   `// \| version`                     |
|   `library.compilers`                 |

-----

## Extra

|                                         |
|                   ---                   |
|   `headers`                             |
|   `vn`                                  |
|   `info.date \| comment.date \| /`      |
|   `info.date2 \| comment.date2 \| /`    |
|   `info.date3 \| comment.date3 \| /`    |
|   `info.unix`                           |
|   `help \| info.pinescript`             |
|   `info.timezone`                       |
|   `operator \| op`                      |
|   `variable`                            |
|   `function`                            |