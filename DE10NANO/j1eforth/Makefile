
.DEFAULT: j1eforth.ice
	silice-make.py -s j1eforth.ice -b $@ -p basic,vga,uart -o BUILD_$(subst :,_,$@)

clean:
	rm -rf BUILD_*
