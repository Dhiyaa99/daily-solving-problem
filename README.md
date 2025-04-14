# daily-solving-problem


def count_high_candels(candels):
    tallest = max(candels)
    return candels.count(tallest)

user_input = input('Enter candels height:')
candels = list(map(int, user_input.split()))

print('Num of the tallest candels is:', count_high_candels(candels))
