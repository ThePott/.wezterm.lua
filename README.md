local wezterm = require("wezterm")
local config = wezterm.config_builder()

config.font = wezterm.font("IntoneMono Nerd Font", { weight = "Regular" })
config.font_size = 23

config.window_padding = {
	left = 0,
	right = 0,
	top = 0,
	bottom = 0,
}

config.enable_tab_bar = false
config.hide_tab_bar_if_only_one_tab = true
config.use_fancy_tab_bar = false
config.window_decorations = "RESIZE"
return config
