import datetimE

def get_day_info():
    now = datetime.datetime.now()
    print(f"Update: {now.strftime('%Y-%m-%d %H:%M:%S')}")
    print("GitHub activity logged successfully!")

if __name__ == "__main__":
    get_day_info()
