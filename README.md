# scriptona_solucao.txt
Comandos_frase
     ┌────────────────────────────────────────────────────────────────────┐
     │                • MobaXterm Personal Edition v22.2 •                │
     │              (X server, SSH client and network tools)              │
     │                                                                    │
     │ ⮞ Your computer drives are accessible through the /drives path     │
     │ ⮞ Your DISPLAY is set to 192.168.1.10:0.0                          │
     │ ⮞ When using SSH, your remote DISPLAY is automatically forwarded   │
     │ ⮞ Your HOME folder is not persistent: it will be erased on restart │
     │ ⮞ Each command status is specified by a special symbol (✓ or ✗)    │
     │                                                                    │
     │ • Important:                                                       │
     │ This is MobaXterm Personal Edition. The Professional edition       │
     │ allows you to customize MobaXterm for your company: you can add    │
     │ your own logo, your parameters, your welcome message and generate  │
     │ either an MSI installation package or a portable executable.       │
     │ We can also modify MobaXterm or develop the plugins you need.      │
     │ For more information: https://mobaxterm.mobatek.net/download.html  │
     └────────────────────────────────────────────────────────────────────┘

  20/11/2022 ►  17:37.03 ►  /home/mobaxterm ► clear
                                                                                                                                        ✓

  20/11/2022 ►  17:37.05 ►  /home/mobaxterm ► grep --help
Usage: /bin/grep [OPTION]... PATTERN [FILE]...
Search for PATTERN in each FILE or standard input.
PATTERN is, by default, a basic regular expression (BRE).
Example: /bin/grep -i 'hello world' menu.h main.c

Regexp selection and interpretation:
  -E, --extended-regexp     PATTERN is an extended regular expression (ERE)
  -F, --fixed-strings       PATTERN is a set of newline-separated fixed strings
  -G, --basic-regexp        PATTERN is a basic regular expression (BRE)
  -P, --perl-regexp         PATTERN is a Perl regular expression
  -e, --regexp=PATTERN      use PATTERN for matching
  -f, --file=FILE           obtain PATTERN from FILE
  -i, --ignore-case         ignore case distinctions
  -w, --word-regexp         force PATTERN to match only whole words
  -x, --line-regexp         force PATTERN to match only whole lines
  -z, --null-data           a data line ends in 0 byte, not newline

Miscellaneous:
  -s, --no-messages         suppress error messages
  -v, --invert-match        select non-matching lines
  -V, --version             print version information and exit
      --help                display this help and exit
      --mmap                use memory-mapped input if possible

Output control:
  -m, --max-count=NUM       stop after NUM matches
  -b, --byte-offset         print the byte offset with output lines
  -n, --line-number         print line number with output lines
      --line-buffered       flush output on every line
  -H, --with-filename       print the filename for each match
  -h, --no-filename         suppress the prefixing filename on output
      --label=LABEL         print LABEL as filename for standard input
  -o, --only-matching       show only the part of a line matching PATTERN
  -q, --quiet, --silent     suppress all normal output
      --binary-files=TYPE   assume that binary files are TYPE;
                            TYPE is `binary', `text', or `without-match'
  -a, --text                equivalent to --binary-files=text
  -I                        equivalent to --binary-files=without-match
  -d, --directories=ACTION  how to handle directories;
                            ACTION is `read', `recurse', or `skip'
  -D, --devices=ACTION      how to handle devices, FIFOs and sockets;
                            ACTION is `read' or `skip'
  -R, -r, --recursive       equivalent to --directories=recurse
      --include=FILE_PATTERN  search only files that match FILE_PATTERN
      --exclude=FILE_PATTERN  skip files and directories matching FILE_PATTERN
      --exclude-from=FILE   skip files matching any file pattern from FILE
      --exclude-dir=PATTERN directories that match PATTERN will be skipped.
  -L, --files-without-match print only names of FILEs containing no match
  -l, --files-with-matches  print only names of FILEs containing matches
  -c, --count               print only a count of matching lines per FILE
  -T, --initial-tab         make tabs line up (if needed)
  -Z, --null                print 0 byte after FILE name

Context control:
  -B, --before-context=NUM  print NUM lines of leading context
  -A, --after-context=NUM   print NUM lines of trailing context
  -C, --context=NUM         print NUM lines of output context
  -NUM                      same as --context=NUM
      --color[=WHEN],
      --colour[=WHEN]       use markers to highlight the matching strings;
                            WHEN is `always', `never', or `auto'
  -U, --binary              do not strip CR characters at EOL (MSDOS)
  -u, --unix-byte-offsets   report offsets as if CRs were not there (MSDOS)

`egrep' means `grep -E'.  `fgrep' means `grep -F'.
Direct invocation as either `egrep' or `fgrep' is deprecated.
With no FILE, or when FILE is -, read standard input.  If less than two FILEs
are given, assume -h.  Exit status is 0 if any line was selected, 1 otherwise;
if any error occurs and -q was not given, the exit status is 2.

Report bugs to <bug-grep@gnu.org>.
                                                                                                                                        ✓

  20/11/2022 ►  17:37.10 ►  /home/mobaxterm ► clear
                                                                                                                                        ✓

  20/11/2022 ►  17:39.03 ►  /home/mobaxterm ► C:/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main
bash: C:/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main: Is a directory
                                                                                                                                        ✗

  20/11/2022 ►  17:40.07 ►  /home/mobaxterm ►
                                                                                                                                        ✗

  20/11/2022 ►  17:40.22 ►  /home/mobaxterm ►
                                                                                                                                        ✗

  20/11/2022 ►  17:40.24 ►  /home/mobaxterm ► cd C:/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:40.29 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:40.39 ► cd passo_10
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:40.45 ► ls
gpl-3.0.txt     instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:40.46 ► grep "freedom" -c gpl-3.0.txt
8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:41.52 ► ls
gpl-3.0.txt     instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:41.57 ► grep -c "freedom" gpl-3.0.txt
8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:42.36 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:42.43 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:42.45 ► cd passo_8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:42.52 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:42.54 ► nano instrucoes.txt
nano: command not found

  nano can be installed using the following command: apt install nano

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:42.59 ►
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:42.59 ► apt install nano


DISCLAIMER:

This will download and install third-party software packages, distributed by
the Cygwin Project, from online Cygwin repositories.
These software packages are distributed under their own terms available here:
http://mirrors.kernel.org/sourceware/cygwin/x86/release
Third-party software packages are neither developed nor distributed by Mobatek.
In no event shall Mobatek be liable for any direct, indirect, incidental,
special, exemplary, or consequential damages (including, but not limited to,
procurement of substitute goods or services, loss of data or profits, computer
virus infection, or business interruption) however caused and on any theory of
liability, whether in contract, strict liability, or tort (including negligence
or otherwise) arising in any way out of the use of these third-party software
packages, even if advised of the possibility of such damage.
By typing "y", you agree to use these third-party programs at your own risks.

Type "y" to continue or any other key to exit: y

The following packages will be installed:
- nano v4.9-1 (577 kB): Enhanced clone of Pico editor
- cygwin v3.3.5-1 (2076 kB): The UNIX emulation engine
- file v5.41-2 (633 kB): Determines file type using 'magic' numbers
- liblzma5 v5.2.5-1 (75 kB): LZMA de/compressor library (runtime)

⮞ Type "y" to download and install these packages (3,28 MB): y


[1/6] Downloading dash-0.5.11.5-1.tar.xz                                    [OK]
[1/6] Installing dash-0.5.11.5-1.tar.xz                                     [OK]
[2/6] Downloading rebase-4.6.1-1.tar.xz                                     [OK]
[2/6] Installing rebase-4.6.1-1.tar.xz                                      [OK]
[3/6] Downloading liblzma5-5.2.5-1.tar.zst                                  [OK]
[3/6] Installing liblzma5-5.2.5-1.tar.zst                                   [OK]
[4/6] Downloading file-5.41-2.tar.xz                                        [OK]
[4/6] Installing file-5.41-2.tar.xz                                         [OK]
[5/6] Downloading cygwin-3.3.5-1.tar.xz                                     [OK]
[5/6] Installing cygwin-3.3.5-1.tar.xz                                      [OK]
[6/6] Downloading nano-4.9-1.tar.xz                                         [OK]
[6/6] Installing nano-4.9-1.tar.xz                                          [OK]
- Replacing old symlinks                                                    [OK]
- Rebasing files                                                            [OK]
- Executing postinstall scripts                                             [OK]
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:43.24 ► pwd
/drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:43.26 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:43.30 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:44.12 ► wget https://www.rcsb.org/fasta/entry/7PND
--2022-11-20 17:44:20--  https://www.rcsb.org/fasta/entry/7PND
Resolving www.rcsb.org... 128.6.159.248
Connecting to www.rcsb.org|128.6.159.248|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 456 [text/x-fasta]
Saving to: ‘7PND’

7PND                               100%[=============================================================>]     456  --.-KB/s    in 0s

2022-11-20 17:44:21 (96,6 MB/s) - ‘7PND’ saved [456/456]

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:44.21 ► ls
7PND            instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:44.24 ► grep -c "k" 7PND
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:44.36 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:44.43 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:44.45 ► cd passo_8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:45.00 ► ls
7PND            instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:45.01 ► nano 7PND
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:45.16 ► grep -c "K" 7PND
1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:45.29 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:45.34 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:45.35 ► nano passo_1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:45.50 ► cd passo_1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_1 ►  master ►
  20/11/2022 ►  17:45.53 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_1 ►  master ►
  20/11/2022 ►  17:45.55 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_1 ►  master ►
  20/11/2022 ►  17:46.07 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:46.18 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:46.20 ► cd passo_2
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_2 ►  master ►
  20/11/2022 ►  17:46.28 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_2 ►  master ►
  20/11/2022 ►  17:46.29 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_2 ►  master ►
  20/11/2022 ►  17:46.42 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:46.45 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:46.46 ► cd passo_5
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_5 ►  master ►
  20/11/2022 ►  17:46.51 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_5 ►  master ►
  20/11/2022 ►  17:46.53 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_5 ►  master ►
  20/11/2022 ►  17:47.09 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:47.11 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:47.12 ► cd passo_10
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:47.16 ► ls
gpl-3.0.txt     instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:47.18 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:47.53 ► wget https://www.gnu.org/licenses/gpl-3.0.txt
--2022-11-20 17:48:12--  https://www.gnu.org/licenses/gpl-3.0.txt
Resolving www.gnu.org... 209.51.188.116, 2001:470:142:5::116
Connecting to www.gnu.org|209.51.188.116|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 35149 (34K) [text/plain]
Saving to: ‘gpl-3.0.txt.1’

gpl-3.0.txt.1                      100%[=============================================================>]  34,33K  --.-KB/s    in 0,1s

2022-11-20 17:48:13 (232 KB/s) - ‘gpl-3.0.txt.1’ saved [35149/35149]

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.13 ► ls
gpl-3.0.txt     gpl-3.0.txt.1   instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.15 ► mv > gpl-3.0.txt
BusyBox v1.22.1 (2015-11-10 11:07:12    ) multi-call binary.

Usage: mv [-fin] SOURCE DEST
or: mv [-fin] SOURCE... DIRECTORY

Rename SOURCE to DEST, or move SOURCE(s) to DIRECTORY

        -f      Don't prompt before overwriting
        -i      Interactive, prompt before overwrite
        -n      Don't overwrite an existing file

                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.30 ► ks
ks: command not found
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.33 ► ls
gpl-3.0.txt     gpl-3.0.txt.1   instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.34 ► grep -c "freedom" gpl-3.0.txt
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:48.48 ► grep -c "freedonm" gpl-3.0.txt
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:49.01 ► grep -c "freedon" gpl-3.0.txt
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:49.07 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:49.32 ► nano gpl-3.0.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:49.47 ► nano gpl-3.0.txt.1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:50.09 ► grep -c "freedom" gpl-3.0.txt.1
8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_10 ►  master ►
  20/11/2022 ►  17:50.26 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:50.32 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  17:50.33 ► cd passo_8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:50.38 ► ls
7PND            instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:50.39 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:51.12 ► grep -c "K" 7PND
1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:51.42 ► nano 7PND
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:52.11 ► grep "K" -c 7PND
1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:52.28 ► grep "*K" -c 7PND
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:52.49 ► grep --help
Usage: /bin/grep [OPTION]... PATTERN [FILE]...
Search for PATTERN in each FILE or standard input.
PATTERN is, by default, a basic regular expression (BRE).
Example: /bin/grep -i 'hello world' menu.h main.c

Regexp selection and interpretation:
  -E, --extended-regexp     PATTERN is an extended regular expression (ERE)
  -F, --fixed-strings       PATTERN is a set of newline-separated fixed strings
  -G, --basic-regexp        PATTERN is a basic regular expression (BRE)
  -P, --perl-regexp         PATTERN is a Perl regular expression
  -e, --regexp=PATTERN      use PATTERN for matching
  -f, --file=FILE           obtain PATTERN from FILE
  -i, --ignore-case         ignore case distinctions
  -w, --word-regexp         force PATTERN to match only whole words
  -x, --line-regexp         force PATTERN to match only whole lines
  -z, --null-data           a data line ends in 0 byte, not newline

Miscellaneous:
  -s, --no-messages         suppress error messages
  -v, --invert-match        select non-matching lines
  -V, --version             print version information and exit
      --help                display this help and exit
      --mmap                use memory-mapped input if possible

Output control:
  -m, --max-count=NUM       stop after NUM matches
  -b, --byte-offset         print the byte offset with output lines
  -n, --line-number         print line number with output lines
      --line-buffered       flush output on every line
  -H, --with-filename       print the filename for each match
  -h, --no-filename         suppress the prefixing filename on output
      --label=LABEL         print LABEL as filename for standard input
  -o, --only-matching       show only the part of a line matching PATTERN
  -q, --quiet, --silent     suppress all normal output
      --binary-files=TYPE   assume that binary files are TYPE;
                            TYPE is `binary', `text', or `without-match'
  -a, --text                equivalent to --binary-files=text
  -I                        equivalent to --binary-files=without-match
  -d, --directories=ACTION  how to handle directories;
                            ACTION is `read', `recurse', or `skip'
  -D, --devices=ACTION      how to handle devices, FIFOs and sockets;
                            ACTION is `read' or `skip'
  -R, -r, --recursive       equivalent to --directories=recurse
      --include=FILE_PATTERN  search only files that match FILE_PATTERN
      --exclude=FILE_PATTERN  skip files and directories matching FILE_PATTERN
      --exclude-from=FILE   skip files matching any file pattern from FILE
      --exclude-dir=PATTERN directories that match PATTERN will be skipped.
  -L, --files-without-match print only names of FILEs containing no match
  -l, --files-with-matches  print only names of FILEs containing matches
  -c, --count               print only a count of matching lines per FILE
  -T, --initial-tab         make tabs line up (if needed)
  -Z, --null                print 0 byte after FILE name

Context control:
  -B, --before-context=NUM  print NUM lines of leading context
  -A, --after-context=NUM   print NUM lines of trailing context
  -C, --context=NUM         print NUM lines of output context
  -NUM                      same as --context=NUM
      --color[=WHEN],
      --colour[=WHEN]       use markers to highlight the matching strings;
                            WHEN is `always', `never', or `auto'
  -U, --binary              do not strip CR characters at EOL (MSDOS)
  -u, --unix-byte-offsets   report offsets as if CRs were not there (MSDOS)

`egrep' means `grep -E'.  `fgrep' means `grep -F'.
Direct invocation as either `egrep' or `fgrep' is deprecated.
With no FILE, or when FILE is -, read standard input.  If less than two FILEs
are given, assume -h.  Exit status is 0 if any line was selected, 1 otherwise;
if any error occurs and -q was not given, the exit status is 2.

Report bugs to <bug-grep@gnu.org>.
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:53.25 ► grep "*K*" -c 7PND
0
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:53.59 ► grep -c "K" 7PND
1
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:56.06 ► cat 7PND
>7PND_1|Chains A, B|BFT-3|Bacteroides fragilis (817)
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDYINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYDDQIYFLIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:56.28 ► awk --help
BusyBox v1.22.1 (2015-11-10 11:07:12    ) multi-call binary.

Usage: awk [OPTIONS] [AWK_PROGRAM] [FILE]...

        -v VAR=VAL      Set variable
        -F SEP          Use SEP as field separator
        -f FILE         Read program from FILE
        -e AWK_PROGRAM

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  17:59.04 ► awk -f "K" 7PND
awk: K: No such file or directory
                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:00.52 ► awk -F "K" 7PND
CLEAR
CLEAR



                                                                                                                                        ✗

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:02.31 ► ls
7PND            instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:02.38 ► grep -o 'K' 7PND | wc -l
24
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:03.19 ► grep -o 'K' 7PND
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
K
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:03.34 ► ls
7PND            instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_8 ►  master ►
  20/11/2022 ►  18:03.42 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:03.46 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:03.48 ► cd passo_24
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:03.59 ► ls
instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:04.01 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:04.34 ► wget https://www.alphafold.ebi.ac.uk/entry/F4HVG8
--2022-11-20 18:04:41--  https://www.alphafold.ebi.ac.uk/entry/F4HVG8
Resolving www.alphafold.ebi.ac.uk... 34.149.152.8
Connecting to www.alphafold.ebi.ac.uk|34.149.152.8|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 7504 (7,3K) [text/html]
Saving to: ‘F4HVG8’

F4HVG8                             100%[=============================================================>]   7,33K  --.-KB/s    in 0,02s

2022-11-20 18:04:43 (459 KB/s) - ‘F4HVG8’ saved [7504/7504]

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:04.43 ► ls
F4HVG8          instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:04.45 ► ls -lh F4HVG8
-rw-r--r--    1 197609   197121      7.3K Nov  1 12:27 F4HVG8
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_24 ►  master ►
  20/11/2022 ►  18:05.16 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:05.24 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:05.26 ► cd passo_7
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:05.33 ► ls
instrucoes.txt      sequences.fasta     sequences_II.fasta
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:05.34 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:06.05 ► cat sequences.fasta
>BFT-3|Bacteroides fragilis (817)
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Bos taurus
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:06.18 ► grep -c ">Homo sapiens" sequences.fasta
6
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:06.56 ► cat sequences_II.fasta
>BFT-3|Bacteroides fragilis (817)
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Bos taurus
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL
>Feliz catus
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILG
>BFT-3 pan troglodites
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTTSIDAPVTASIDLQSVSYTDLATQLNDVSDFGKMIILKDNGFNRQVHVSMDKRTKIQLDNENVRLFNGRDKDSTNFILGDEFAVLRFYRNGESISYIAYKEAQMMNEIAEFYAAPFKKTRAINEKEAFECIYDSRTRSAGKYPVSVKINVDKAKKILNLPECDDQIYFLIRWGTWDNN
>Echerichia Coli
YINDYIKTPQVPHGITESQTRAVPSEPKTVYVICLRENGSTVYPNEVSAQMQDAANSVYAVHGLKRYVNLHFVLYTTEYACPSGNADEGLDGFTASLKANPKAEGYD
>Homo sapiens
MGSSHHHHHHSSGENLYFQGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGANHADDPKDLMYSKYTGYLFHLSEKNMDIIAKNLGWEIADGD
>Teania Saginata
ILGISWLNSYNVNTASDFKASGMSTTQLMYPGVMAHELGHILGGAMACSNEADSLTIRWGTWDNNILGISWLNSYNVNTASDFKASGMSTTQL

                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:07.22 ► grep -c ">Homo sapiens" sequences_II.fasta
3
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:07.37 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_7 ►  master ►
  20/11/2022 ►  18:07.54 ► cd ..
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:07.57 ► ls
LICENSE     passo_1     passo_11    passo_2     passo_24    passo_4     passo_44    passo_5     passo_8     passo_91
README.md   passo_10    passo_12    passo_20    passo_3     passo_42    passo_48    passo_7     passo_9     welcome.sh
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main ►  master ►
  20/11/2022 ►  18:07.58 ► cd passo_9
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:08.03 ► ls
arch1.doc       arch2.doc       arch_I.md       arch_II.md      arch_III.md     arch_IV.md      arch_V.md       doc1.doc        instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:08.04 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:08.31 ► touch frase_final.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:08.44 ► ls
arch1.doc        arch_I.md        arch_III.md      arch_V.md        frase_final.txt
arch2.doc        arch_II.md       arch_IV.md       doc1.doc         instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:08.45 ► nano instrucoes.txt
                                                                                                                                        ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:09.00 ► cat *.md
**"A liberdade se aprende exercendo-a."Clara Campoamor
Obrigada por participar deste desafio** 🤗                                                                                                ✓

  /drives/c/Users/Lenovo/Desktop/Pre-Camp/Final_Work/projeto_final_pre-camp_wbds_la-carmenbarragan-main/passo_9 ►  master ►
  20/11/2022 ►  18:09.10 ► cat sequences.fasta

