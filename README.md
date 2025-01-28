# show-Setty
This is a lab02 and assignment work for developing WebApps and Services 44563-01
# Hi! This is Viswas performing WebApps lab02
### One of my most favorite foods: Hyderabadi-Dum Biryani
I love Hyderabadi-Dum Biryani because it is a perfect combination of **aromatic spices** and is a **dish of celebration**.
This dish comes into play during various occasions and the slow cooking process is what gives the dish a more flavorful and aromatic taste.
***
## Places I can get
1. **Home-made** : Although it is a little hard to match as similarly as a hotel dish, it can be made in our homes.
2. **Pista House** : In Hyderabad, It is a must try dish at Pista House.
3. **Naidu gari Kunda Biryani** : It is served in a clay pot.

- The three side dishes i would have with are
- Kaju mutton
- Raitha
- Omlette

![More about my Favorite movie](https://github.com/ViswasS/show-Setty/blob/main/MyMovie.md)
---
### Alternative Actors for Oppenheimer
While Cillian Murphy is the Lead Actor who delivered an historical performance, here are some more actors who could also fulfill that role.
Willem Dafoe, Suraj Sharma, Benedict Cumberbatch, Christian Bale
| Actor Name            | Reason of Choice                                                                      | Age |
|-----------------------|---------------------------------------------------------------------------------------|----|
| Willem Dafoe          | Known for his intense and energitic roles                                             | 69 |
| Benedict Cumberbatch  | Exceptional in portryaing intellectuals and complex characters (The Imitation Game)   | 48 |
| Christian Bale        | Master of transformation, brings dept and commitment to his every role (The Prestige) | 50 |
| Dev Patel             | Younger and charismatic, with potential to bring a fresh perspective (The Man Who Knew Infinity) | 34 |
***
### Favorite Quotes
> "In the middle of every difficulty lies opportunity."
> *- Albert Einstein*

> "Be alone, that is the secret of invention; be alone, that is when ideas are born."
> _- NiKola Tesla_
***
## Find difference between lists using dart
Below is a Dart code snippet that demonstrates how to find difference of lists.
The function takes two iterables (`a` and `b`), converts the second iterable to a set, and returns a new list containing elements in `a` that `b` does not contain.


```dart

List difference(Iterable a, Iterable b){
        final s = b.toSet();
        return a.where((x) => !s.contains(x)).toLisT();
    }
```

Source: Example Snippet- <https://code.pieces.app/collections/dart>