# SPDX-License-Identifier: GPL-2.0
dtbo-y += samsung/a14x/a14x_eur_open_w00_r04.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r05.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r00.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r06.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r02.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r03.dtbo
dtbo-y += samsung/a14x/a14x_eur_open_w00_r01.dtbo
dtbo-y += samsung/m14x/m14x_eur_open_w00_r03.dtbo
dtbo-y += samsung/m14x/m14x_eur_open_w00_r00.dtbo
dtbo-y += samsung/m14x/m14x_eur_open_w00_r01.dtbo
dtb-y += exynos/s5e8535.dtb
dtbo-y += exynos/board/erd/s5e8535-erd8535_r1f.dtbo
dtbo-y += exynos/board/erd/s5e8535-erd8535.dtbo
dtbo-y += exynos/board/erd/s5e8835-erd8835.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always-y  := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
