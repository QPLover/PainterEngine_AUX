from building import *
Import('rtconfig')

pe_dir = GetCurrentDir() + '/../PainterEngine-latest'

path = []
src = []

path = [pe_dir + '/core', pe_dir + '/kernel']
src += Glob(pe_dir + '/core/*.c')
src += Glob(pe_dir + '/kernel/*.c')

group = DefineGroup('PainterEngine', src, depend=['PKG_USING_PAINTERENGINE'], CPPPATH=path)

Return('group')
