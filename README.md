The Microbial–ENzyme Decomposition (MEND) model with Freeze–Thaw dynamics (MEND-FT) explicitly represents soil freeze–thaw processes and their effects on microbial activity, with particular emphasis on microbial dormancy strategies.


MEND-FT integrates freeze-thaw front generation into the MEND model so that freezing depth (`Fdep`) and thawing depth (`Tdep`) are calculated internally from model input soil temperature and soil water content.


The model supports two freeze-thaw regimes:

- `iALT_type = 0`: seasonally frozen soil
- `iALT_type = 1`: permafrost

All `Fdep/Tdep` values are in `cm`.

