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
















              Raw Audio Recordings (4 files, ~5 GB)
                │
 ┌──────────────┴──────────────┐
 │                             │
 ▼                             ▼
Time-Domain Analysis       Frequency-Domain Analysis
 │                             │
 ├───────────────┐             ├────────────────────────┐
 │               │             │                        │
Waveform     Rolling Leq   Spectrograms (time/freq)   PSD (Welch/Periodogram)
Peak detect  Leq trends    Band energy splits         Power spectrum
 │               │             │                        │
 └───────┬───────┘             └──────────────┬─────────┘
         ▼                                   ▼
        Spectral Statistics (mean/median PSD, level distributions)
                                │
                 ┌──────────────┴──────────────┐
                 │                             │
        Z-weighted Leq                 A-weighted Leq
   (physical measurement)       (human hearing perception)
                                │
                ┌───────────────┴───────────────┐
                │                               │
         Comparisons                      Compliance / Insights
   (overlay, averages, trends)     (WHO/NAAQS limits, histograms,
                                   diurnal variation, octave bands,
                                   significance tests)

                          ▼
                       Results
          (Tables, plots, statistics, discussion)

