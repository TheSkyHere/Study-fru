主要使用工具 frugen (github)


使用样例(chassis)：
./frugen --board-mfg "Biggest International Corp." \
    --chassis-type 0x17 \
    --chassis-pn "XX0123456789ABCDE002" \
    --chassis-seria "XX0123456789ABCDE001A000000003" \
    --chassis-custom "XXXX" \
    --board-date "10/1/2017 12:58:00" \
    --board-mfg "XX0123456789A001" \
    --board-pname "XXXX" \
    --board-serial "XX0123456789ABCDE001A000000002" \
    --board-pn "XX0123456789ABCDE001" \
    --board-custom "XXXX" \
    --prod-mfg "XX0123456789A001" \
    --prod-name "XXXX" \
    --prod-modelpn "XX0123456789ABCDE001" \
    --prod-version "V123" \
    --prod-serial "SN00112233445566" \
    --prod-atag "XX0123456789ABCDE001TAG0000002" \
    --prod-custom "XXXX" \
    --binary --board-custom "01020304FEAD1E" \
    OCP_BB_fru.bin



./frugen --board-mfg "Biggest International Corp." \
    --board-date "10/1/2017 12:58:00" \
    --board-mfg "XX0123456789A001" \
    --board-pname "XXXX" \
    --board-serial "XX0123456789ABCDE001A000000002" \
    --board-pn "XX0123456789ABCDE001" \
    --board-custom "XXXX-node0" \
    --prod-mfg "XX0123456789A001" \
    --prod-name "XXXX" \
    --prod-modelpn "XX0123456789ABCDE001" \
    --prod-version "V123" \
    --prod-serial "SN00112233445566" \
    --prod-atag "XX0123456789ABCDE001TAG0000002" \
    --prod-custom "XXXX" \
    --binary --board-custom "01020304FEAD1E" \
    OCP_CPU0_fru.bin