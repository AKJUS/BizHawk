TARGET := opera.wbx
CCFLAGS := 	-I. \
		-Iopera-libretro \
		-Iopera-libretro/libopera \
		-Iopera-libretro/libretro-common/include \
		-Iopera-libretro/deps \
		-Iopera-libretro/deps/lzma-19.00/include \
		-Iopera-libretro/deps/libchdr/include \
		-Iopera-libretro/deps/zlib-1.2.11 \
		-DHAVE_CHD \
		-D_7ZIP_ST \
		-DDR_FLAC_NO_STDIO \
		-D__LIBRETRO__ \
		-DNDEBUG \
		-DHAVE_CDROM \
		-DHAVE_STDINT_H \
		-DHAVE_STDLIB_H \
		-DHAVE_SYS_PARAM_H \
		-DINLINE=inline \
		-DTHREADED_DSP
CXXFLAGS := $(CCFLAGS) 
SRCS =  bizhawk.cpp \
		opera-libretro/lr_input.c \
		opera-libretro/libretro_core_options.c \
		opera-libretro/lr_input_crosshair.c \
		opera-libretro/opera_lr_nvram.c \
		opera-libretro/libopera/opera_mem.c \
		opera-libretro/libopera/opera_diag_port.c \
		opera-libretro/libopera/prng32.c \
		opera-libretro/libopera/opera_sport.c \
		opera-libretro/libopera/opera_arm.c \
		opera-libretro/libopera/opera_region.c \
		opera-libretro/libopera/opera_bios.c \
		opera-libretro/libopera/prng16.c \
		opera-libretro/libopera/opera_cdrom.c \
		opera-libretro/libopera/opera_clock.c \
		opera-libretro/libopera/opera_log.c \
		opera-libretro/libopera/opera_fixedpoint_math.c \
		opera-libretro/libopera/opera_nvram.c \
		opera-libretro/libopera/opera_3do.c \
		opera-libretro/libopera/opera_xbus_cdrom_plugin.c \
		opera-libretro/libopera/opera_madam.c \
		opera-libretro/libopera/opera_dsp.c \
		opera-libretro/libopera/opera_state.c \
		opera-libretro/libopera/opera_xbus.c \
		opera-libretro/libopera/opera_bitop.c \
		opera-libretro/libopera/opera_vdlp.c \
		opera-libretro/libopera/opera_clio.c \
		opera-libretro/libopera/opera_pbus.c \
		opera-libretro/libretro.c \
		opera-libretro/retro_cdimage.c \
		opera-libretro/opera_lr_callbacks.c \
		opera-libretro/opera_lr_opts.c \
		opera-libretro/deps/zlib-1.2.11/zutil.c \
		opera-libretro/deps/zlib-1.2.11/adler32.c \
		opera-libretro/deps/zlib-1.2.11/inflate.c \
		opera-libretro/deps/zlib-1.2.11/inftrees.c \
		opera-libretro/deps/zlib-1.2.11/crc32.c \
		opera-libretro/deps/zlib-1.2.11/infback.c \
		opera-libretro/deps/zlib-1.2.11/inffast.c \
		opera-libretro/deps/lzma-19.00/src/BraIA64.c \
		opera-libretro/deps/lzma-19.00/src/CpuArch.c \
		opera-libretro/deps/lzma-19.00/src/Sort.c \
		opera-libretro/deps/lzma-19.00/src/Bra86.c \
		opera-libretro/deps/lzma-19.00/src/Alloc.c \
		opera-libretro/deps/lzma-19.00/src/LzmaEnc.c \
		opera-libretro/deps/lzma-19.00/src/Lzma86Dec.c \
		opera-libretro/deps/lzma-19.00/src/Delta.c \
		opera-libretro/deps/lzma-19.00/src/LzmaDec.c \
		opera-libretro/deps/lzma-19.00/src/Lzma86Enc.c \
		opera-libretro/deps/lzma-19.00/src/LzFind.c \
		opera-libretro/deps/libchdr/src/libchdr_cdrom.c \
		opera-libretro/deps/libchdr/src/libchdr_flac.c \
		opera-libretro/deps/libchdr/src/libchdr_bitstream.c \
		opera-libretro/deps/libchdr/src/libchdr_chd.c \
		opera-libretro/deps/libchdr/src/libchdr_huffman.c \
		opera-libretro/cuefile.c \
		opera-libretro/opera_lr_dsp.c \
		opera-libretro/libretro-common/string/stdstring.c \
		opera-libretro/libretro-common/vfs/vfs_implementation_cdrom.c \
		opera-libretro/libretro-common/vfs/vfs_implementation.c \
		opera-libretro/libretro-common/encodings/encoding_utf.c \
		opera-libretro/libretro-common/file/retro_dirent.c \
		opera-libretro/libretro-common/file/file_path.c \
		opera-libretro/libretro-common/compat/compat_strl.c \
		opera-libretro/libretro-common/compat/fopen_utf8.c \
		opera-libretro/libretro-common/compat/compat_snprintf.c \
		opera-libretro/libretro-common/compat/compat_posix_string.c \
		opera-libretro/libretro-common/compat/compat_strcasestr.c \
		opera-libretro/libretro-common/streams/file_stream.c \
		opera-libretro/libretro-common/streams/chd_stream.c \
		opera-libretro/libretro-common/streams/interface_stream.c \
		opera-libretro/libretro-common/streams/file_stream_transforms.c \
		opera-libretro/libretro-common/streams/memory_stream.c \
		opera-libretro/libretro-common/rthreads/rthreads.c \
		opera-libretro/libretro-common/lists/dir_list.c \
		opera-libretro/libretro-common/lists/string_list.c \
		opera-libretro/libretro-common/cdrom/cdrom.c \
		opera-libretro/libretro-common/memmap/memalign.c \
		opera-libretro/libretro-common/memmap/memmap.c \
		opera-libretro/lr_input_descs.c 

include ../common.mak
