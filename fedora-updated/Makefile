help:
	@echo "make build-31       - Build fedora-updated:31"
	@echo "make force-build-31 - Build fedora-updated:31 ignoring cached images"
	@echo "make build-30       - Build fedora-updated:30"
	@echo "make force-build-30 - Build fedora-updated:30 ignoring cached images"
	@echo "make build-29       - Build fedora-updated:29"
	@echo "make force-build-29 - Build fedora-updated:29 ignoring cached images"
	@echo "make build-28       - Build fedora-updated:28"
	@echo "make force-build-28 - Build fedora-updated:28 ignoring cached images"

build-31:
	podman build --file OCIfile.31 -t fedora-updated:31 .

force-build-31:
	podman pull fedora:31
	podman build --file OCIfile.31 -t fedora-updated:31 --no-cache .

build-30:
	podman build --file OCIfile.30 -t fedora-updated:30 .

force-build-30:
	podman pull fedora:30
	podman build --file OCIfile.30 -t fedora-updated:30 --no-cache .

build-29:
	podman build --file OCIfile.29 -t fedora-updated:29 .

force-build-29:
	podman pull fedora:29
	podman build --file OCIfile.29 -t fedora-updated:29 --no-cache .

build-28:
	podman build --file OCIfile.28 -t fedora-updated:28 .

force-build-28:
	podman pull fedora:28
	podman build --file OCIfile.28 -t fedora-updated:28 --no-cache .
