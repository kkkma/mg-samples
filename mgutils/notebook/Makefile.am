SUBDIRS=res
LDADD=-lmgutils

noinst_PROGRAMS=notebook

CUSTOMMG_SRC=custom_minigui.c
notebook_SOURCES=main.c notebook.h notebook_res_cn.h \
				 notebook_res_en.h notebook_res_tw.h $(CUSTOMMG_SRC)

EXTRA_DIST=big5.txt  gb2312.txt

