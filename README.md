# Aikatsu Planet Ranking DB

```ts
{
  name: string;
  type: "プラネットポイント" | "ハイスコア" | "連勝数" | "タッチしたノーツの数" | "ドレシアチャンスボーナス";
  data: {
    rank: string;
    imgb64: string;
    name: string;
    phrase: string;
    point: string;
    partner: null | {
      name: string;
      phrase: string;
      imgb64: string;
    };
  }[];
}
```
