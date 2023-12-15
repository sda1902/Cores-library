=====================================================================================================================================================
																X32CsSRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32Carrier core
	ISet:									X32Cs
	Cache:									None
	Instruction cache:						one-way 4Kx128
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes
	Modules:
		X32CsSRAM.sv
		Library/PortalMC.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFOCs.sv
		Library/TFifoS.sv
		Library/StreamController32Cs.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32Cs.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/MUX64X32Cs.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32Cs.sv
		Library/FpuMasterRAM.sv
		Library/FPU32Cs.sv
		Library/FPMUL128V.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/Flash32.sv
		Library/EU64X32Cs.sv
		Library/ALU64X32.sv
		Library/DMux.sv
		Library/ContextCTRL32Cs.sv
	MIF Files:
		X32Kernel0							X32 Kernel, memory byte 0
		X32Kernel1							X32 Kernel, memory byte 1
		X32Kernel2							X32 Kernel, memory byte 2
		X32Kernel3							X32 Kernel, memory byte 3
		X32Kernel4							X32 Kernel, memory byte 4
		X32Kernel5							X32 Kernel, memory byte 5
		X32Kernel6							X32 Kernel, memory byte 6
		X32Kernel7							X32 Kernel, memory byte 7
		MESSENGER32Cs.mif					Messenger microcode
		CONTEXT32Cs.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X32CsCache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32Carrier core
	ISet:									X32Cs
	Cache:									4-way, 64KByte
	Instruction cache:						one-way 4Kx128
	Main memory interface:					64-bit interface to the QDR SRAM memory controller 
	Modules:
		X32CsCache4x64x2048.sv
		Library/PortalMC.sv
		Library/Cache4x64x2048.sv 
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFOCs.sv
		Library/TFifoS.sv
		Library/StreamController32Cs.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32Cs.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/MUX64X32Cs.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32Cs.sv
		Library/FpuMasterRAM.sv
		Library/FPU32Cs.sv
		Library/FPMUL128V.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/Flash32.sv
		Library/EU64X32Cs.sv
		Library/ALU64X32.sv
		Library/DMux.sv
		Library/ContextCTRL32Cs.sv
	MIF Files:
		X32Kernel0							X32 Kernel, Boot memory byte 0
		X32Kernel1							X32 Kernel, Boot memory byte 1
		X32Kernel2							X32 Kernel, Boot memory byte 2
		X32Kernel3							X32 Kernel, Boot memory byte 3
		X32Kernel4							X32 Kernel, Boot memory byte 4
		X32Kernel5							X32 Kernel, Boot memory byte 5
		X32Kernel6							X32 Kernel, Boot memory byte 6
		X32Kernel7							X32 Kernel, Boot memory byte 7
		MESSENGER32Cs.mif					Messenger microcode
		CONTEXT32Cs.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X32CsCache4x512x1024
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32Carrier core
	ISet:									X32Cs
	Cache:									256K /4x512x1024/
	Instruction cache:						one-way 4Kx128
	Main memory interface:					Avalon-MM interface of the DDR3 SDRAM Controller with UniPHY /data bus 512 bit, 4x burst mode, quarter rate suitable/
	Modules:
		X32CsCache4x512x1024.sv
		Library/PortalMC.sv
		Library/Cache4x512x1024DDR3.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFOCs.sv
		Library/TFifoS.sv
		Library/StreamController32Cs.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32Cs.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/MUX64X32Cs.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32Cs.sv
		Library/FpuMasterRAM.sv
		Library/FPU32Cs.sv
		Library/FPMUL128V.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/Flash32.sv
		Library/EU64X32Cs.sv
		Library/ALU64X32.sv
		Library/DMux.sv
		Library/ContextCTRL32Cs.sv
	MIF Files:
		X32Kernel0							X32 Kernel, Boot memory byte 0
		X32Kernel1							X32 Kernel, Boot memory byte 1
		X32Kernel2							X32 Kernel, Boot memory byte 2
		X32Kernel3							X32 Kernel, Boot memory byte 3
		X32Kernel4							X32 Kernel, Boot memory byte 4
		X32Kernel5							X32 Kernel, Boot memory byte 5
		X32Kernel6							X32 Kernel, Boot memory byte 6
		X32Kernel7							X32 Kernel, Boot memory byte 7
		MESSENGER32Cs.mif					Messenger microcode
		CONTEXT32Cs.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X32CsISI
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32Carrier core
	ISet:									X32Cs
	Cache:									none
	Instruction cache:						one-way 4Kx128
	Main memory interface:					ISI
	Modules:
		X32CsISI.sv
		Library/PortalMC.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFOCs.sv
		Library/TFifoS.sv
		Library/StreamController32Cs.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32Cs.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/MUX64X32Cs.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32Cs.sv
		Library/FpuMasterRAM.sv
		Library/FPU32Cs.sv
		Library/FPMUL128V.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/Flash32.sv
		Library/EU64X32Cs.sv
		Library/ALU64X32.sv
		Library/DMux.sv
		Library/ContextCTRL32Cs.sv
	MIF Files:
		X32Kernel0							X32 Kernel, Boot memory byte 0
		X32Kernel1							X32 Kernel, Boot memory byte 1
		X32Kernel2							X32 Kernel, Boot memory byte 2
		X32Kernel3							X32 Kernel, Boot memory byte 3
		X32Kernel4							X32 Kernel, Boot memory byte 4
		X32Kernel5							X32 Kernel, Boot memory byte 5
		X32Kernel6							X32 Kernel, Boot memory byte 6
		X32Kernel7							X32 Kernel, Boot memory byte 7
		MESSENGER32Cs.mif					Messenger microcode
		CONTEXT32Cs.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file




=====================================================================================================================================================
=====================================================================================================================================================
											Prototype cores. They DON'T have Carrier capabilities
=====================================================================================================================================================
=====================================================================================================================================================

=====================================================================================================================================================
																X32SRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32 experimental core /without carrier ability/ has embedded FFT and Multiplier-accumulator units
	ISet:									X32 /with FFT and FMULLACC instructions/
	Cache:									none
	Instruction cache:						one-way 4Kx128
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes
	Modules:
		X32SRAM.sv
		Library/TFifoS.sv
		Library/StreamController32.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/Neuro32.sv
		Library/MUX64X32.sv
		Library/MultichannelFIFO.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32.sv
		Library/FpuMasterRAM.sv
		Library/FPU32.sv
		Library/FPMUL128V.sv
		Library/FPMUL32.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash32.sv
		Library/FFTCache.sv
		Library/fft.sv
		Library/EU64X32.sv
		Library/ErrorFIFO.sv
		Library/DMux.sv
		Library/ContextCTRL32.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/ALU64X32.sv
	MIF Files:
		X32Kernel0							X32 Kernel, memory byte 0
		X32Kernel1							X32 Kernel, memory byte 1
		X32Kernel2							X32 Kernel, memory byte 2
		X32Kernel3							X32 Kernel, memory byte 3
		X32Kernel4							X32 Kernel, memory byte 4
		X32Kernel5							X32 Kernel, memory byte 5
		X32Kernel6							X32 Kernel, memory byte 6
		X32Kernel7							X32 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT32.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X32Cache4x512x1024
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X32 experimental core /without carrier ability/ has embedded FFT and Multiplier-accumulator units
	ISet:									X32 /with FFT and FMULLACC instructions/
	Cache:									256K /4x512x1024/
	Instruction cache:						one-way 4Kx128
	Main memory interface:					Avalon-MM interface of the DDR3 SDRAM Controller with UniPHY /data bus 512 bit, 4x burst mode, quarter rate suitable/
	Modules:
		X32Cache4x512x1024.sv
		Library/TFifoS.sv
		Library/StreamController32.sv
		Library/Shifter64X32.sv
		Library/SFifo.sv
		Library/Sequencer32.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/Neuro32.sv
		Library/MUX64X32.sv
		Library/MultichannelFIFO.sv
		Library/Mult108.sv
		Library/Mult53.sv
		Library/Mult24.sv
		Library/Misc64X32.sv
		Library/Microcontroller.sv
		Library/Messenger32.sv
		Library/FpuMasterRAM.sv
		Library/FPU32.sv
		Library/FPMUL128V.sv
		Library/FPMUL32.sv
		Library/FPDIV128V.sv
		Library/FPADD128V.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash32.sv
		Library/FFTCache.sv
		Library/fft.sv
		Library/EU64X32.sv
		Library/ErrorFIFO.sv
		Library/DMux.sv
		Library/ContextCTRL32.sv
		Library/Cache4x512x1024DDR3.sv
		Library/ALU64X32.sv
	MIF Files:
		X32Kernel0							X32 Kernel, memory byte 0
		X32Kernel1							X32 Kernel, memory byte 1
		X32Kernel2							X32 Kernel, memory byte 2
		X32Kernel3							X32 Kernel, memory byte 3
		X32Kernel4							X32 Kernel, memory byte 4
		X32Kernel5							X32 Kernel, memory byte 5
		X32Kernel6							X32 Kernel, memory byte 6
		X32Kernel7							X32 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT32.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16ISI
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 experimental core
	ISet:									X16
	Cache:									none
	Instruction cache:						one-way 4Kx64
	Main memory interface:					ISI
	Modules:
		X16ISI.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/StreamControllerX16.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/SequencerX16.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/PrefetcherX16.sv
		Library/Neuro16.sv
		Library/MUX64X16.sv
		Library/Mult108.sv
		Library/Misc64X16.sv
		Library/Microcontroller.sv
		Library/Messenger16.sv
		Library/FpuMasterRAM.sv
		Library/FPU16.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fftX16.sv
		Library/EU64X16.sv
		Library/FFTCache.sv
		Library/ALU64X16.sv
		Library/DMux.sv
		Library/ContextCTRL16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16SRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 experimental core
	ISet:									X16
	Cache:									none
	Instruction cache:						one-way 4Kx64
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes
	Modules:
		X16SRAM.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/StreamControllerX16.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/SequencerX16.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/PrefetcherX16.sv
		Library/Neuro16.sv
		Library/MUX64X16.sv
		Library/Mult108.sv
		Library/Misc64X16.sv
		Library/Microcontroller.sv
		Library/Messenger16.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/FpuMasterRAM.sv
		Library/FPU16.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fftX16.sv
		Library/EU64X16.sv
		Library/FFTCache.sv
		Library/ALU64X16.sv
		Library/DMux.sv
		Library/ContextCTRL16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16Cache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 experimental core
	ISet:									X16
	Cache:									4-way, 64KByte
	Instruction cache:						one-way 4Kx64
	Main memory interface:					64-bit interface to the QDR SRAM memory controller
	Modules:
		X16Cache4x64x2048.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/StreamControllerX16.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/SequencerX16.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/PrefetcherX16.sv
		Library/Neuro16.sv
		Library/MUX64X16.sv
		Library/Mult108.sv
		Library/Misc64X16.sv
		Library/Microcontroller.sv
		Library/Messenger16.sv
		Library/Cache4x64x2048.sv 
		Library/FpuMasterRAM.sv
		Library/FPU16.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fftX16.sv
		Library/EU64X16.sv
		Library/FFTCache.sv
		Library/ALU64X16.sv
		Library/DMux.sv
		Library/ContextCTRL16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16Cache4x256x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 experimental core
	ISet:									X16
	Cache:									256K /4x256x2048/
	Instruction cache:						one-way 4Kx64
	Main memory interface:					Avalon-MM interface of the DDR3 SDRAM Controller with UniPHY /data bus 256 bit, 4x burst mode, half rate suitable/
	Modules:
		X16Cache4x256x2048.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/StreamControllerX16.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/SequencerX16.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/PrefetcherX16.sv
		Library/Neuro16.sv
		Library/MUX64X16.sv
		Library/Mult108.sv
		Library/Misc64X16.sv
		Library/Microcontroller.sv
		Library/Messenger16.sv
		Library/Cache4x256x2048DDR3.sv
		Library/FpuMasterRAM.sv
		Library/FPU16.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fftX16.sv
		Library/EU64X16.sv
		Library/FFTCache.sv
		Library/ALU64X16.sv
		Library/DMux.sv
		Library/ContextCTRL16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16Cache4x512x1024
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 experimental core
	ISet:									X16
	Cache:									256K /4x512x1024/
	Instruction cache:						one-way 4Kx64
	Main memory interface:					Avalon-MM interface of the DDR3 SDRAM Controller with UniPHY /data bus 512 bit, 4x burst mode, quarter rate suitable/
	Modules:
		X16Cache4x512x1024.sv
		Library/sc_fifo_thr.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/StreamControllerX16.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/SequencerX16.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/PrefetcherX16.sv
		Library/Neuro16.sv
		Library/MUX64X16.sv
		Library/Mult108.sv
		Library/Misc64X16.sv
		Library/Microcontroller.sv
		Library/Messenger16.sv
		Library/Cache4x512x1024DDR3.sv
		Library/FpuMasterRAM.sv
		Library/FPU16.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fftX16.sv
		Library/EU64X16.sv
		Library/FFTCache.sv
		Library/ALU64X16.sv
		Library/DMux.sv
		Library/ContextCTRL16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16ESRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 with extended instruction pathes experimental core
	ISet:									X16
	Cache:									none
	Instruction cache:						one-way 4Kx64
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes
	Modules:
		X16ESRAM.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/MUX64X16.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/Flash16.sv
		Library/EU64X16E.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerX16E.sv
		Library/Neuro16.sv
		Library/SFifo.sv
		Library/fftX16.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPU16.sv
		Library/RTE.sv
		Library/StreamControllerX16.sv
		Library/ContextCTRL16.sv
		Library/Messenger16.sv
		Library/Microcontroller.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16ECache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							X16 with extended instruction pathes experimental core
	ISet:									X16
	Cache:									4-way, 64KByte
	Instruction cache:						one-way 4Kx64
	Main memory interface:					64-bit interface to the QDR SRAM memory controller
	Modules:
		X16ECache4x64x2048.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/MUX64X16.sv
		Library/Cache4x64x2048.sv 
		Library/Flash16.sv
		Library/EU64X16E.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerX16E.sv
		Library/Neuro16.sv
		Library/SFifo.sv
		Library/fftX16.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPU16.sv
		Library/RTE.sv
		Library/StreamControllerX16.sv
		Library/ContextCTRL16.sv
		Library/Messenger16.sv
		Library/Microcontroller.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16x2SRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Double X16 experimental cores
	ISet:									X16
	Cache:									none
	Instruction cache:						one-way 4Kx64 per core
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes per core
	Modules:
		X16x2SRAM.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/MUX64S2.sv
		Library/MUX64S2SL.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/Flash16.sv
		Library/EU64S2.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerX16.sv
		Library/Neuro16.sv
		Library/SFifo.sv
		Library/FFT.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPU16.sv
		Library/RTE.sv
		Library/StreamControllerS2.sv
		Library/ContextCTRL16.sv
		Library/Messenger16.sv
		Library/Microcontroller.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16x2Cache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Double X16 experimental cores
	ISet:									X16
	Cache:									4-way, 64KByte per core
	Instruction cache:						one-way 4Kx64 per core
	Main memory interface:					Two 64-bit interface to the QDR SRAM memory controller
	Modules:
		X16x2Cache4x64x2048.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/MUX64S2.sv
		Library/MUX64S2SL.sv
		Library/Cache4x64x2048.sv 
		Library/Flash16.sv
		Library/EU64S2.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerX16.sv
		Library/Neuro16.sv
		Library/SFifo.sv
		Library/FFT.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPU16.sv
		Library/RTE.sv
		Library/StreamControllerS2.sv
		Library/ContextCTRL16.sv
		Library/Messenger16.sv
		Library/Microcontroller.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16x4Cache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Quad X16 experimental cores
	ISet:									X16
	Cache:									4-way, 64KByte per core
	Instruction cache:						one-way 4Kx64 per core
	Main memory interface:					Four 64-bit ISI interfaces
	Modules:
		X16x4Cache4x64x2048.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFO.sv
		Library/TFifoS.sv
		Library/MUX64S4.sv
		Library/MUX64S4SL.sv
		Library/Cache4x64x2048.sv 
		Library/Flash16.sv
		Library/EU64S4.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerX16.sv
		Library/Neuro16.sv
		Library/SFifo.sv
		Library/FFT.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPU16.sv
		Library/RTE.sv
		Library/StreamControllerS4.sv
		Library/ContextCTRL16.sv
		Library/Messenger16.sv
		Library/Microcontroller.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER.mif						Messenger microcode
		CONTEXT16.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16DTSRAM
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Dual-Thread X16 experimental core
	ISet:									X16
	Cache:									none
	Instruction cache:						one-way 4Kx64 per thread
	Main memory interface:					Internal static memory 256K/512K/1M/2M bytes per core
	Modules:
		X16DTSRAM.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFODT.sv
		Library/TFifoS.sv
		Library/MUX64DT.sv
		Library/InternalMemory256K.sv
		Library/InternalMemory512K.sv
		Library/InternalMemory1M.sv
		Library/InternalMemory2M.sv
		Library/Flash16.sv
		Library/EU64V0T2.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerDT.sv
		Library/Neuro32.sv
		Library/SFifo.sv
		Library/fftX16.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPUDT.sv
		Library/RTE.sv
		Library/StreamController32.sv
		Library/ContextCTRLDT.sv
		Library/MessengerDT.sv
		Library/MicrocontrollerDT.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGERDT.mif						Messenger microcode
		CONTEXTDT.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																X16DTCache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Dual-Thread X16 experimental core
	ISet:									X16
	Cache:									4-way, 64KByte
	Instruction cache:						one-way 4Kx64 per thread
	Main memory interface:					Four 64-bit ISI interfaces
	Modules:
		X16DTCache4x64x2048.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/MultichannelFIFO.sv
		Library/ErrorFIFODT.sv
		Library/TFifoS.sv
		Library/MUX64DT.sv
		Library/Cache4x64x2048.sv 
		Library/Flash16.sv
		Library/EU64V0T2.sv
		Library/DMux.sv
		Library/PrefetcherX16.sv
		Library/SequencerDT.sv
		Library/Neuro32.sv
		Library/SFifo.sv
		Library/fftX16.sv
		Library/FFTCache.sv
		Library/FPMUL32.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/FPADD128.sv
		Library/FPMUL128.sv
		Library/Mult108.sv
		Library/FPDIV128.sv
		Library/ALU64X16.sv
		Library/Shifter64X16.sv
		Library/Misc64X16.sv
		Library/FPUDT.sv
		Library/RTE.sv
		Library/StreamController32.sv
		Library/ContextCTRLDT.sv
		Library/MessengerDT.sv
		Library/MicrocontrollerDT.sv
		Library/FpuMasterRAM.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGERDT.mif						Messenger microcode
		CONTEXTDT.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file

=====================================================================================================================================================
																T2X16T2X32Cache4x64x2048
-----------------------------------------------------------------------------------------------------------------------------------------------------
	Library edition:						Intel(Altera)
	Description:							Quad-Thread, Two X16 and two X32 threads experimental core
	ISet:									X16 and X32
	Cache:									4-way, 64KByte
	Instruction cache:						one-way 4Kx64 per X16 thread and 4Kx128 per X32 thread
	Main memory interface:					64-bit ISI interface
	Modules:
		T2X16T2X32Cache4x64x2048.sv
		Library/Cache4x64x2048.sv
		Library/StreamController4T.sv
		Library/Shifter64X32.sv
		Library/Shifter64X16.sv
		Library/SFifo.sv
		Library/Sequencer32.sv
		Library/SequencerX16.sv
		Library/sc_fifo_thr.sv
		Library/sc_fifo.sv
		Library/RTE.sv
		Library/Prefetcher32M.sv
		Library/PrefetcherX16.sv
		Library/Neuro32.sv
		Library/Neuro16.sv
		Library/MUX64T4.sv
		Library/MultichannelFIFO.sv
		Library/Mult108.sv
		Library/Misc64X32.sv
		Library/Misc64X16.sv
		Library/Microcontroller4T.sv
		Library/Messenger4T.sv
		Library/FpuMasterRAM.sv
		Library/FPU4T.sv
		Library/FPMUL128V.sv
		Library/FPMUL128.sv
		Library/FPMUL32.sv
		Library/FPDIV128V.sv
		Library/FPDIV128.sv
		Library/FPADD128V.sv
		Library/FPADD128.sv
		Library/FPADD32.sv
		Library/FPACC32.sv
		Library/Flash16.sv
		Library/fft32.sv
		Library/FFTCache.sv
		Library/FFT.sv
		Library/EU64x32MT.sv
		Library/EU64x16MT.sv
		Library/ErrorFIFOQT.sv
		Library/DMux.sv
		Library/ContextCTRL4T.sv
		Library/Arbiter.sv
		Library/ALU64X32.sv
		Library/ALU64X16.sv
	MIF Files:
		X16Kernel0							X16 Kernel, memory byte 0
		X16Kernel1							X16 Kernel, memory byte 1
		X16Kernel2							X16 Kernel, memory byte 2
		X16Kernel3							X16 Kernel, memory byte 3
		X16Kernel4							X16 Kernel, memory byte 4
		X16Kernel5							X16 Kernel, memory byte 5
		X16Kernel6							X16 Kernel, memory byte 6
		X16Kernel7							X16 Kernel, memory byte 7
		MESSENGER4T.mif						Messenger microcode
		CONTEXT4T.mif						Context Controller microcode
		TRAM.mif							Transaction RAM init file
		Cache.mif 							Cache init file
		LRU.mif								FPU init file
		DRAM.mif							FPU init file
		FreeRAM.mif							Context controller init file
