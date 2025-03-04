FROM almalinux:9
CMD [ "google.com" ]
# CMD can be overriden 
# ENTRYPOINT can't bve overriden, if try to override it will append to existing,
# for the best results we can use both together.
# we can mention command in entry point and default options or inputs can be passed through CDM
# only one CMD and ENTRYPOINT is allowed to use in a Doclerfile    
ENTRYPOINT [ "ping" ]
