# $FreeBSD$

PKGNAMESUFFIX=	-cubietruck

COMMENT=	Cross-build U-Boot loader for Cubietruck

LICENSE=	GPLv2

# Local overrides
MASTERDIR=	${.CURDIR}/../u-boot-cubieboard
DESCR=		${.CURDIR}/pkg-descr
MODEL=		cubietruck
CONF_TARGET=	Cubietruck_defconfig

.include "${MASTERDIR}/Makefile"
