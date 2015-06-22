My entry for CCJam 2015.

# cload
## Features
inheritance (of course)
static types (-> no type checking for function arguments; variable types still possible)
a big callstack (based on the fact that every coroutine can have it's own 256calls sized callstack -> 50*256 = 10496 calls height)
enums
executable class archives (like jar files in java)
operator overloading
	
## usage
	os.loadAPI("path/to/cload")
	cload.startLoading "basepath/"
	
	cload.loadDirectory "/mydirectoryinbasepath"
	
	cload.load()
	cload.run()
