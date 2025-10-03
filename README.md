# audio-insights
Audio analysis project (spectrograms, SPL, pressure)

   /*               Raw Audio Recordings 
                                   │
                 ┌─────────────────┴──────────────────┐
                 │                                    │
        Time-Domain Analysis                  Frequency-Domain Analysis
                 │                                    │
   ┌─────────────┴───────────────┐         ┌──────────┴─────────────────┐
   │                             │         │                            │
Waveform (amplitude vs time)   Rolling     Spectrograms (t/f)          PSD (Welch /Periodogram)
Peak detection (max events)    Leq trends  Band energy splits           Power spectrum
   │                             │         │                            │
   └─────────────┬───────────────┘         └──────────┬─────────────────┘
                 │                                    │
                 └───────────────► Spectral Statistics ◄───────────────┘
                                 (mean/median PSD, level distributions)
                                   │
                            Psychoacoustic Weighting
                            ┌──────────────┴──────────────┐
                            │                             │
                    Z-weighted Leq (physical)     A-weighted Leq (human hearing)
                                   │
                     ┌─────────────┴───────────────┐
                     │                             │
                 Comparisons                   Compliance / Insights
         (Overlay, Average, Summary)     (WHO/NAAQS limits, histograms,
                                        diurnal variation, octave bands,
                                          statistical significance tests)
                                   
                            Results
              (Tables, Plots, Statistical summaries, Discussion)














https://pmc.ncbi.nlm.nih.gov/articles/PMC9869818/#Sec14
