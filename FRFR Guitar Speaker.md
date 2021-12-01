# FRFR Guitar Speaker [DIY]
1. FR為1米1W測量之曲線
   1. 額定功率(RMS)可能因喇叭材料限制，80%、90%
2. 先決定腔體or單體
   1. 腔體:ID已限制
   2. 單體:喇班單體選擇有限
      1. 先挑低頻
         1. 因為高頻好挑且限制不多
         2. 低頻選擇多
3. Driver
   1. 分類
      1. 完美Full Range
         1. Fo:30Hz
         2. Frequency Range(+-10dB):20kHz
         3. 瓦數越大越好
         4. Sensitivity:90db
            1. 1米1瓦1kHz的音壓值
         5. 現實中
            1. 100~10k
      2. Mid :
         1. 低頻堪用(60)
         2. 高頻掛(4k)
      3. Twitter
         1. 2k~15k
      4. Woofer
         1. 60~1k
      5. Ex:
         1. Woofer+Full
         2. Mid+Twitter
   2. 由於低頻喇叭需要配合條件多
      1. 腔體體積
      2. 種類多:sub-woofer、woofer、mid-range
      3. 低音補強
         1. 風管(荷姆茲頻率、可創造更底頻(風管內部))
         2. Passive Radiator(利用背壓能量，可創造更底頻(PR材質、大小))
            1. 不可開洩音孔
         3. 調整空氣阻尼
            1. 調整背壓
               1. 讓Fo脫離氣密腔體限制，中低頻自然下沉，回復無限障版狀態。
            2. 洩音孔開口大小粗條
            3. 網布細調(可調整中頻洩漏量/加強中頻)
   3. Impedance
4. 腔體
   1. 專注於輔助低頻，由於
   2. TS
      * Q:懸吊軟硬度(電的impedance/機構懸吊)
        * Qts:Total Q of the speaker
        * Qes:Speaker electrical Q
        * Qtc:加上腔體後的聲學反應表現
      * Fs:Free air resonance of speaker in Hz
      * Vas:Volume of air equal to the speakers spring characteristics in liters
      * Pmax:Maximum power of the driver in watts(放大器功率)
      * Diameter:The diameter of the driver in cm(從懸邊最高點計算直徑)
      * Xmax:The amount of cone movement in one direction in mm (單體最大振福)
      * Dp:Diameter of the port(s) in cm(風管直徑)
      * Ports:Number of ports(風管數量)
5. 開發儀器(研發參數調整參照)
   1. AP:Amplifier
      1. 整合高階示波器/電表、可於兩線式連接下，精準自動化量測電學參數。
   2. Klippel:單體
      1. 藉由雷射量測振福、搭配四線式連接法(差分量測法)，可自動化精準回推於非線性震動狀態時，研發所需的參數(磁通量)
6. 檢測工具(產線檢測產品表現、相對便宜)
   1. SoundCheck:聲學
      1. 檢驗成品整體聲學表現的經濟方案
