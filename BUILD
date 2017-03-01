genrule(
	name = 'foo',
	outs = ['foo.txt'],
	cmd = '''perl -ne 's/bar/foo/' < $(location :input.txt) > $@''',
	tools = [':input.txt'],
)
