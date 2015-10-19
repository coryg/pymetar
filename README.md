# pymetar
Python 3 library for parsing METAR weather observation data

This is a port of python-metar to Python3.

= Sample Usage

'''
from metar import METARObservation

obs = METARObservation("METAR KXNA 162053Z 01009KT 10SM CLR 19/00 A3034 RMK AO2 SLP269 T01940000")

print(obs.temp)
'''