# Master_project_codes
The python code for the GUI and the used Arduino scetecher for reading the AD4776

## The Arduino codes

The arduino codes are accociated of the wirings presented in the report of my masters project.

--Capa_extended_I2CmultiplexVlot.ino is associated of wiring 1 in the section of the second devices. 

--Capacitance_diff_mod.ino is associated with the wiring 3 in the section of the second devices. 

--Capacitance_mes_ext_mod.ino is associated with the wiring 2 in the section of the second devices and the wiring of the first devices.

## The python 3.7.1 GUI code

Make shure to have installe the following libraries:

--pyserial

--matplotlib

--tkinter

--pandas

--numpy


The two python GUI codes are acociated to the data recorded during the experiments.

--GUI_for_read_2CDC_Volts.py is used for the record of capacitance singal A and B and the Voltage read by the Arduino ADC

--GUI_for_capa_applyV.py is used for reading 1 measurement signal at once. So for the experiments where the overall capacitance is read. Additionally the applied voltage is set with thiy GUI.
