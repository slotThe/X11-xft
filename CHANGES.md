# Change Log / Release Notes

## unknown

  * Dropped support for GHC 7.10.

  * Added `xftDrawStringFallback`, which works like `xftDrawString` but
    supports font fallback.

  * Added `xftTextAccumExtents`, which works like `xftTextExtents` but
    possibly uses different fonts for different parts of the string and
    returns the accumulative extents.

  * Added the functions `xftfont_max_ascent`, `xftfont_min_descent`, and
    `xftfont_max_height` to gain information about a non-empty list of
    `XftFont`s.

## 0.3.3 (2021-05-09)

  * Fixed flipped green/blue values in XRenderColor.
