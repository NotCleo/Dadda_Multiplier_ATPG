## Dadda_Multiplier_ATPG
Automatic Test Pattern Generation for Dadda Multiplier


#### Run Atalanta with Fault list (-f), Test output (-t), and Benchmark netlist (-v)
    
    atalanta -f daddafault.flt -t daddatest.test -v daddabench.bench
    • .bench: The gate-level netlist converted to bench format.
    • .test: The output file that contains the test vectors generated.
    • .flt: The output report listing detected stuck-at faults.
