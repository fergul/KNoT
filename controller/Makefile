CFLAGS += -DWITH_UIP=1 -I -DDEBUG=1
PROJECT_SOURCEFILES+= ../knot_protocol.c ../knot_network.c ../knot_uip_network.c ../channeltable.c ../knot_channel_state_uip.c knot-controller.c 
CONTIKI_PROJECT = app-controller
all: $(CONTIKI_PROJECT)
CONTIKI =/home/user/contiki
include $(CONTIKI)/Makefile.include