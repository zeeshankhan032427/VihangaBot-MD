[let setting = global.db.data.settings[botNumber]
            if (typeof setting !== 'object') global.db.data.settings[botNumber] = {}
	    if (setting) {
		if (!isNumber(setting.status)) setting.status = 0
const send = `${global.autobio}`
		if (!('autobio' in setting)) setting.autobio = send
	    } else global.db.data.settings[botNumber] = {
		status: 0,
		autobio: send,
	    }
](https://github.com/vihangayt0/CheemsBot-MD2/generate)


https://github.com/vihangayt0/CheemsBot-MD2/generate
