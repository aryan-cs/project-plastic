
# Project Plastic

Using mealworms (tenebrio molitor) & computer vision to identify types of plastic & decompose/upcycle them.


## Authors

- [Aryan Gupta (@aryan-cs)](https://www.github.com/aryan-cs)


## Resources

 - [Rob Jordan, Stanford News, 2019](https://news.stanford.edu/2019/12/19/mealworms-provide-plastic-solution/)
 - [Rob Jordan, Stanford News, 2015](https://news.stanford.edu/pr/2015/pr-worms-digest-plastics-092915.html)
 - [Yang et al, 2015](https://pubs.acs.org/doi/abs/10.1021/acs.est.5b02661)
 - [Plastic Tracker](https://theoceancleanup.com/plastic-tracker/)
 - [The World Counts](https://www.theworldcounts.com/challenges/planet-earth/oceans/plastic-in-the-ocean)
 - [Filament Extruder Product by ArtMe3D](https://artme-3d.shop/products/diy-kit-2)
 - [Filament Extruder Demo](https://www.youtube.com/watch?v=BT04glGDjB4)

## Notes

- Verified that mealworms are able to sustain themselves on a pure styrofoam diet
- The styrofoam group did not turn to cannibalism, the organic group often did
- Mealworms shy away from heat (temperatures greater than 80°F) and operate best around 75°F
- Mealworms were indifferent to lighting & color
- Movement & activity greatly slow in heavily fungus-ridden environments 
- Classifier worked best with plain, dark backgrounds
- Noticed a "fishy" smell from the styrofoam group, but not from the organic group
- As of 02/03/2024, the organic group has a high mortality rate (>25%) compared to the styrofoam group (0%)
- As of 02/23/2024, over 6 fully grown beetles have been found in the organic group, and 2 from the styrofoam group (almost all mealworms from the styrofoam group have refrained from metamorphosis)
- As of 03/12/2024, no darkling beetles have died from the styrofoam-only diet


## Visuals

| ![Mealworms 1](https://lh3.googleusercontent.com/pw/ABLVV87lk1xWdQZOO9NSrI9jcsOMQPZj0k5MRLBLQkk7f88Uj5duxbQZn039BZnckPgxzj198xeQift9ZJ1u5wDjPQJjt8NDL19tfcU74mXlbKEDLunGmKOAOXLdms-kWblyQZQG-mHfUIzIhPtBwBEhHmuOo4X9LC8hsG6icEFZoQ4HlrG76F9TVTNzqIwPtoPb4fpx82DoSSdHVbJhWcaudIgM62LkUG0rrSg60e9v1lVjqSQR4FriNxsg6vvCegIog81-4NcQZYVsztAAOfluY0yNthOOltVNjrXqSlGOs6Qg8i6-4TwBfzzO5wq-Ax8j65ADYFs22tF96Z2lBRYAbEclrTgkvBAOz_JmEGGHQjomyf9BZHbgSgkqqbH5H1xcLW1HWdPyZ8BIAI7B32KvO2cVccSCbs0r0EeaUTop9CDOstEHGw_QziiC_nL2cnoE-7fSx5XwwK4iMtaBqTgN2iymWTXb04zYIKSYosE-WrDzkqVOKB-6RdfwclnQQorPvTZmnqmH58lUhiSV-pWGODAGD2p3RfD_yP2xo_yJpaD_dMtIy-7aQZ8jrGLQPqKvZx4XraiJu9g-YVUnf8i8f6HBWf5qNcxSCrgSLd2PdtRvRhLtD-uQ-MU_ExxXLjwnEwfFa7nVFzDQH0bPmN3mlrvvOqbMqBlc0M5LWKWLQiYPLX-9D4VdSrywyNTwJmWd_eyJqTDPxl3LI9fH_gusol35GVuhZtfYnKqXTxm1JZyCOywX2yETr02DTBx9-18EI4-hS_iTdpj2X3EdfIl56fYLZMJaB5U6OB2OgDLmeHrz5HdG9_oR5emyxpG_igNRqZYW9eOzKkvF_kGp2U02iqA4i2L3167Zg7U6xMxxIzAAeBQyBMOA4GPrrrL5HG6-zaVA6SkZxL3iCgtZVNxlxQj524Rp9VksB1fRbVK2dp1RRey0KM4OPdMVz8MbPSG6QLvsbilNp_Rxn4uC7HQPmvZ9CZf-wUax4g=w259-h347-no?authuser=0) | ![Mealworms 2](https://lh3.googleusercontent.com/pw/ABLVV87djJ4M9TlKGsqvkyGGFEWsrQuX6KbzS8UnZfaw5JhfbDKWRlo_h1_KwlfQ1ZB2k71J3zo2KJjc-DqJLC4kKE2Ye35YsFGS_rmMo9rKO24c6oqqRZhB5fVVoVO1MVjouhW1VY8Koak8pyFf15fh_LPnMrJkrzkPDPr1BbjGzsjfD6-2pHHhNLkott18by9bp5XKhmBIZ1ZSTsSvy5GQwjTeN9diikY0ErMLrp-tcbvToIIM0gchHt9azmZYkF8qrK2TRLSl89npN5MoIQgDcr7Ctj1V38s5rIj8cIJM7zdK40LNYxAFizTs8h1xSDi5yIeHPab-kaT3x4mLUJaL0StzHGUsNnfCjAUDDhmMHG_iQKEQCqdJ-Il33WPpiwW0XwP-U0NseAMyowvuM4NmUw1I-WGYt78ePuRXpo0II1RU6xlfbCeL6WMHmCA7_AqdAbyx6eRcHm3L7O-dlaSlL-KPyREZhFxT6A3pIIR3dO3N60FopmCntrKA65VL779lOnbTihyWPcabqQ4GknK7i4-aF_SEYT19b1ZCD48LTP2yll4XhDCUd82jaCF6gCUBtjGrNNX4jpriHZWLM45_jU_1GTZQbwxHfaBOHEkorhOBmtDK2kMJoSf-mVsBEokwdQ-5o6fYdb2mdlpLEP-8gh7jzYt_7jtrngMgvIE6ueIgiVrtvQU0xW0bCZjw6_UtbjtUOtduwqtZ3DumNdE5F1jnB0Ubbb_v0DkGEAc1UTR3M1CeaB2CTvFwBHtSo2fcnlXwS_VcNUu0q4tLnpxcWfOET4_Plc6bepc0v-kp0zST9obdmDF1Ng8KOr8X8-acxFn1bwkyUsdiwp2srOje26FTRTKlWvAJ7Ch-tmYJPeifzYmvnhSfvHqwMxhOGGvonwwXnaWIDhrjq5B3Lg30Fi_d_KQeVy_wjve8MC_r9eZSJtk6zzc-rAJhEMtYHPlVCk8pIoYmVnezdlA6T9NF_AY4HZAWIv2Qgw=w260-h347-no?authuser=0) | ![Mealworms 3](https://lh3.googleusercontent.com/pw/ABLVV84qgLAqeoG3UicReZHbn-b90VSUqrsk3SM0p-xgO_NoEoOnEEiAKSlGnjnM7SnnVdnzQnTN8RhO_g3TGu5LD0w8QhvTg5TAHTktn-T-N3Psog1W5zlbpoOW1ycy38msf0wpTSR4XtN_-cW58aqZpDkrcIOjMi_3ZI5Bu2igyZCSzNg0rxPcld6VMYWfumNSeUp1sFCxCFQoCub1FLMAJLK13jScsgOKqgKyw1gH0hx0AhCX-xoGwJkQbtBVOgG73BYCQKErKNr-HW2aCqBjVll2-1coyGnJYSLOjJDZxCxU3S_Imh7EGOk94XaEvTR27GC2uyx9h_Ik-hSQUfppws2GctVMsqtC6LygQRF-Z1Vy_qliHXLQ-z7FBFNKDc6PI9L1iFPuXcMXJQW_eG_4Z7pWnFLpbcTL06h-GNEI6DMmf2QsQT90o15pqYj3aYREp1cjbJ-cDHvK0cPzv6Xkk8ZAWCikFfiliSM3lZp9uYyqdIOEkN6DzfHs4Cb4XkIWDFgMVFplQdpdfKUEzydLiEICjZaaipiOc3QrTGqGbCy6cEedUWTeSVPTcfY5yWjg6n1EhFnMFByUGfERCZDWipzFysCFhWWE6-R33BTcKLzeKY3GZHQMXhgv2l6wp8dVoBDTljmjrL-oRSo7kVtEQVZcjdbouWIYaOZsEGxkxLAOU0muUUaukBi3H4q3EB-1wqvKE8PKNIZNJUDHyZqeGQs5q_6ri1AKd1f9S3F7jQ0TSeqk4w2miRUXehMUpaGzVqs2yXOdZs26bnIX09dotYwE7pL3ZrASPqI2shc_koHVAfKaCfRHrtE2290eYxXDc49KfOr-qIXPZAM5hfE0fT_HzwUsjCua_M4JQg-E-hq836OrFoTXuRKFEUSlwr5vHMxh12HIfjkTZwwccq9A3q1ODlAAt6oZMfpOi70UNBL3SjfXR35C9uHOfE_hPOTQUDZjf2suJtm1E3QS06yebZkl0qnC0x2YzA=w260-h347-no?authuser=0) |
|     :---:      |     :---:      |     :---:      |
| ![Mealworms 4](https://lh3.googleusercontent.com/pw/ABLVV8777BjazFYUlc3DaBOmp7fqcd1vN20dnaqWyZrfGJWS5-Bd2m3w5NOgHVpz0YpGeCLyxh_UnA6IE4QNkMF_DUOO9uIMkXzGmPnRJMJetQSfpp61E37m7qyrOgeIMwFqnDcX_fyMeX0Kd2oO6j8ZJLL0Nrnx5L7Lfro8PFuIPqh7VPUQycfjn_k4B10-6h46IE0KH43G0UH3KJV6KS3GS8Aqbik4Qv5wLSU8x1s6cg_pbwpLeNXASTk1W5OkOYv9VNNQELwEi1SjTT-XgV2Zogb6BhbMtrZheNEd_N-sX75H1Y3v5oNzuEs5IlkTrfo8ohRziS25Zux7sQloNxk3FWV6Hd8ZYRJHpu3YvcdDX6v1OnR2dKPtkkt_M8eXn-UP-E9J4mFk6iK7Gx9Hw_TpwAVPMihdQ3UyQO2_2x1U5ZNdPgGHAgglPTLrAtBjZQ0Gf-jjMavegnwhN9f9i7bEkxAG1fcEV55ZhqbVb00EzWnYlvvLlsXHhEvKQb-1rvK8KqCO81NRC5W0nnA36Y3WZJt1ztYkypyBIyTQZXmZMoWc9ga9DNT7d7uWhKmmmPinwN0UIkLiXEmlZTjuUBZ4tRZezh6qeJT8xr4IxTDVYCH-N_vT9475eKh8noKjB8_WPIYye7PMxET4eXJI0qCqrO1iLeF8YFfo-JkK7XvWTIQ7Ric6N1QdbHbtW0HM8wJoETJ2U6iBrsIKEyKPRhxon0pxuA_kKgqqyIni8iLfpRz56cprlLGTp4WEMF2tG4hOpUYTDCig4dO3Nrk9IguFPm06c19j4_XrMyU9u0qBki9Jzf2h7eT-dVFs-SAQFmmi2JJI1BAhlcfqunfqHW9Fd8KPbQUQUYyvXTmdTZ0iACpy0HQ6gFvOfkqFDpo297rjO4Wr3Bgk2Js0tN4-GgkX1OIR9zAEt20P53KXnfEjqpKT2rgD0Mg9wBjz1bcYjT626ucSMP3XixxqrUTLCjhBQ3p8FdxmqCqTEA=w260-h347-no?authuser=0) | ![Mealworms 5](https://lh3.googleusercontent.com/pw/AP1GczOwEdVF8mO41p-OxhzVuV8bqn4qrFQGpq6oi62O1BXFjA2I6sAHm7RAxYBbB14J494evYR38u6NNNGmd-jqalRoehvdQGi7mvrrmoL3WIM4KxUgRCTxjePFs-Lgcnnf6TzKxM78MvGbYwT8PTgr5y6t4cdDJ4kBauwbHgLpxtznzhAr5-9-eBbu2WWoM4oSRpelo3kPQQLSWyTYzoiGiui3ufGLADalsIiOIXRXuSxDMdaLu1DYRHs1l3z7vTAZcEOkwwhxF2ptR5wfi0s1A39QJWrg2iD8nxW6V9UiiqZjpH2lufWiRMGhJYuR0KH2bDCCs6dPMOqfJl8kN2KXXPH4m5BPSVeNQqa9juAX_ekE3W2Vz_7gLCZc-2zo5TcHxhFtqIifGPRVgm_tSbk_8ZohgnEQcapXP3stnyxt_A-oOX8sPfT_zZETW1qZrNSoe_iigWPeVykNRsnH9R35kR3yrQh8RrSGJRo_T-VgJjhSKITB2SFpeJukXeFrMiIdBTGldRbOqY397XZE__3aV6mDzb-NzJtJQOde_RQc6tFbaRWk_87B9o1uU0u9Qm0F-ElT5EgDI59OIiw03hB_tmBWjdGOXuumd58PAMRz6UFOISOIQ1PJwK7d8y1LaimJwiczzXuaY6Qn8z3AkEE3P-Zhd0geEPMXs-y6e2YCsqEC1zpNAhutFMCxs8fn2aJcMz7Q8NOUq7v9IJ509PmzWreNmqkdi9iuc5CRbHXJrDhNSi1sGPS21F0YkO6rtzJbrAfAGzjB3csAg3ZMrbWSsZYQESQ8eSXTJsTK5JzK-64CstDIp8XcCa94LNA9jENWOwJO0vKGe14w75AZ7XgJgFuaUOvzdFJ4WdF3rZQRz0wUL5IHAsFHiyXDeJiay9gvy4IjsQ0JIMnARYuRhzCHgTksF8ksgF_XSfRo7MNfoqEWk4LW4AMFB8Zh6w7fBmjSQEchyD1v4_jrY5Psi0H38lgh_STHRDD7C8r0YHr1H98f8wRGAyLxfX7EoKVdEY4HNEPTVVlYbJstLP_zPRTI-FMLcpiYIp0YdJKZlPglUrBW19h3s_IChlz8l8Kxd0REChD9iNHQe24JL9MuDBDPaH_RQ4Or8JRpsT6wPGWVytngy2tfj5wqTm_Coa6swjEKJDqQO1vfAC3p1fyWwbr6Gk4nHP6tLBBj7j7EcxrxIFG4RIKD3gJh85ypqltCIySyFJAB07M2lWOLxptxa3kZzl2lNZiUjrgix3zVOc3e-opz=w260-h347-no?authuser=0&quot) | ![Mealworms 6](https://lh3.googleusercontent.com/pw/ABLVV84g9phIv8F_rk-OIUM5i9tlAeeHZQ4a3vN-lb98OnoZ9p4vU5j-dLLuukXzGl1-kySuf9jHFM1CCcGNWBf-j_FqjSeo0SOp8z4Rqp0HmXdRtJbjDthgI6l0CtchYuku7zLPdxTZkGeSJEQC6EkddUEVyomaLuWDhBrdLBim9eYpCFOvAD5iJMDlK2vC4VRTPUs4EAbR-1R92SvKdOmR3Q_TD3auWajy8uRXOORWMDLKWXmjsqIph3gYAfEmjjNwcdMkNSjDu5uHVLUtezaYGgWMllz1Zs5wivcqT_GzGrqM--s4jdWScCvHAUraKbWsraZcvnBr_m2OfZ0XuY1YAXRbEFZcP7FOHqUzbzIMWkK_kDqbQqc22tEb8V3C0x4rblpLpYDpb3Qdo2Tsd3zj7gcIFNMO_9MppSHogACQUF-RBG8969K2GNzZmTMVBvDbFFp-AN2H61QYmDDGgGTtU5PcyvbWkq3_x0i3udtoyFBPRzid_g6uY9ai7rmTFW7F3z8Fd1ZWEi_FA6z8Xr_N_Wf52blZTl-UxQMpmNjc0-6eAuDPMX7gk87kaUCAJjznxlvSfsIeXpX5FQulakwFlbwQZm8Hj_eFifIcopijcR-GtfrVaHK-0uLk7zJLGX2eZEuIkoy-4LTJ93wvRhiKtSKtZEyAFk7-_0uYmiI7xfqyc5SwsvaFWN7z3iZa-kwbAfgup6PfopgDHJnL3sSl-pyybPyh6PFYFZV48OYE02xZ0ON136J1fdGplW6TTeSuTHrf8-Rii7smjxJTIcwDNHxha2v-xxh5xLloT7rYIzjwoo81GnbOZXq4MTWatVziob-Vj3U1oE1mNoL8ZeMNWCmMgGtsuEHCAX85DYdCZr2_A8w3p4ElmOkGVbFI6-jVZXMjyT1bO6_XKJYhhG8yhdLRE5Z1pIZU7OI9lrcZZB0MCCc_rwtODBClpmQibn8wRIJiErZOdX1hjzU4HyeVOUT4da2jWPQcFQ=w260-h347-no?authuser=0) |






## Optimizations

 - [Turning to super worms (zophobas morio) in place of mealworms](https://medium.com/climate-conscious/5-plastic-eating-worms-3eace65e4bce)


## Contributing

Contributions are always welcome! Please fork the repository and create a pull request to contribute changes.
