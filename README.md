# Quran.com Open Graph Image Generator

## Tech Stack

- [Next.js](https://nextjs.org/)
- [Satori](https://github.com/vercel/satori)

## How to use

1. Main Image

![Quran.com](https://og.qurancdn.com/api/og)

`https://og.qurancdn.com/api/og`

Optional query parameters:

- `lang` - Image locale. Defaults to `en`.

---

2. Chapter Image

![Quran.com](https://og.qurancdn.com/api/og/chapter/1)

`https://og.qurancdn.com/api/og/chapter/[chapterId]`

Required parameters:

- `[chapterId]` - Chapter number from 1-114.

Optional query parameters:

- `lang` - Image locale. Defaults to `en`.
- `verse` - Verse number.

---

3. About the Quran Image

![Quran.com](https://og.qurancdn.com/api/og/about-the-quran)

`https://og.qurancdn.com/api/og/about-the-quran`


Optional query parameters:

- `lang` - Image locale. Defaults to `en`.
