RB_ADD_GBENCHMARK(HistBenchmarks
  TFormulaBenchmarks.cxx
  TFormulaGradientBenchmarks.cxx
  LABEL short
  LIBRARIES Core Hist MathCore)

RB_ADD_GBENCHMARK(THistBenchmarks
   THistFillBenchmarks.cxx
   LABEL short
   LIBRARIES Hist Core)
