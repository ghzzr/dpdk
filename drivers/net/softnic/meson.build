# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2018 Intel Corporation

allow_experimental_apis = true
install_headers('rte_eth_softnic.h')
sources = files('rte_eth_softnic_tm.c',
	'rte_eth_softnic.c',
	'rte_eth_softnic_mempool.c',
	'rte_eth_softnic_swq.c',
	'rte_eth_softnic_link.c',
	'rte_eth_softnic_tap.c',
	'rte_eth_softnic_action.c',
	'rte_eth_softnic_pipeline.c',
	'rte_eth_softnic_thread.c',
	'rte_eth_softnic_cli.c',
	'parser.c',
	'conn.c')
deps += ['pipeline', 'port', 'table', 'sched']
