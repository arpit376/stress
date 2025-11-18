"""
gen_syslogs.py
Generate messages that end up in the system journal (viewable with journalctl).

Usage examples:
  python3 systd.py --rate 1           # 1 message per second
  
  python3 systd.py --rate 5 --count 10 --tag myapp

  
  python3 systd.py --rate 0.5 --level WARNING
  
"""
