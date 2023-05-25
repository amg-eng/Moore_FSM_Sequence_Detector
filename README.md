# Moore_FSM_Sequence_Detector
detect Moore FSM Sequence in the input signal.
The output of the Moore FSM only goes high when a "1011" sequence is discovered by the Moore FSM, which continuously monitors a binary sequence from a digital input. The following illustration depicts the state diagram of the Moore FSM for the sequence detector.
|**Present state**|**Next state**|**Output**|
|-------------|----------------|----------------|
||**X = 0**|**X = 1**|**X = 0**|**X = 1**|
|2|O(n)|O(1)|
|3|O(n)|O(1)|
|4| O(ologn)|O(1)|
|5| O(ologn)|O(1)|
