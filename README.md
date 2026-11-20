python3 eval/run_eval.py --limit 1                  # quick proof: 1 challenge, both conditions
python3 eval/run_eval.py                            # full challenge set, skills vs baseline
python3 eval/run_eval.py --conditions skills        # skills-on only
python3 eval/run_eval.py --model claude-opus-4-8    # change model (constant across conditions)
