1. Place the folder in EEGLAB's plugins folder.
2, Find your EEGLAB version, copy the two .m files in the "replace" folder to corresponding EEGLAB folder, overwriting the existing one (backup the original one first!). These two files do not actually calculate ICA but are needed to call CUDAICA from GUI and command line. Other EEGLAB versions are not tested. You can also study them and modify by yourself :).

-- END --
