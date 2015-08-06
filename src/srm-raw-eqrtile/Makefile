
#
#   make - configuration
#

    SRM_NAME=srm-raw-eqrtile

#
#   make - synchronize
#

    all:directories
	cp src/$(SRM_NAME) bin/$(SRM_NAME)
	cp src/$(SRM_NAME)-kernel bin/$(SRM_NAME)-kernel

#
#   make - directories
#

    directories:
	mkdir -p bin

#
#   make - clean
#

    clean:
	rm bin/* -f
