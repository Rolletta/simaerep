# eval_sites() must throw warning if stats returned by sim_sites() include NA and subsequently maintain NA values

    Code
      df_eval <- eval_sites(df_sim_sites, r_sim_sites = 100)
    Condition
      Warning in `warning_na()`:
      
      study_id: C, site_number: a, a prob_low value contains NA
      
      study_id: C, site_number: b, a prob_low value contains NA
      
      study_id: C, site_number: c, a prob_low value contains NA
      Warning in `warning_na()`:
      
      study_id: C, site_number: a, a prob_low value contains NA
      
      study_id: C, site_number: b, a prob_low value contains NA
      
      study_id: C, site_number: c, a prob_low value contains NA

