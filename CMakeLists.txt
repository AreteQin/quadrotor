px4_add_module(
	MODULE examples__quadrotor
	MAIN quadrotor
	SRCS
		quadrotor.c
	DEPENDS
		px4_work_queue
	)
