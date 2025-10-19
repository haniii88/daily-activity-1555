import datetim

def show_today():
    today = datetime.datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    print(f"Hello GitHub! Today’s date and time is: {today}")

if __name__ == "__main__":
    show_today()

