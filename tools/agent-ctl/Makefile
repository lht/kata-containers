# Copyright (c) 2020 Intel Corporation
#
# SPDX-License-Identifier: Apache-2.0
#

include ../../utils.mk

default: build

build:
	@RUSTFLAGS="$(EXTRA_RUSTFLAGS) --deny warnings" cargo build --target $(TRIPLE) --$(BUILD_TYPE)

clean:
	cargo clean

vendor:
	cargo vendor

test:

install:

check:

.PHONY: \
	build \
	test \
	check \
	install \
	clean \
	vendor
