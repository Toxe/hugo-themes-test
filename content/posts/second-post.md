+++
date = '2026-04-27T18:06:09+02:00'
draft = true
title = 'Second Post'
tags = ["blog", "content"]
+++
## Let's keep on going

The quest for content continues and the blog needs to grow.

So here is a code block!

```cpp {lineNos=true}
#include <iostream>
#include <string>

struct Value {
    std::string name;
    int value1;
    float value2;
};

Value return_value()
{
    return {"value", 3, 0.7f};
}

int main()
{
    auto v1 = return_value();
    auto [name, a, b] = return_value();

    std::cout << v1.name << ": " << v1.value1 << ", " << v1.value2 << "\n";
    std::cout << name << ": " << a << ", " << b << "\n";
}
```

Hic cum uterque me intueretur seseque ad audiendum significarent paratos, Primum, inquam, deprecor, ne me tamquam philosophum putetis scholam vobis aliquam explicaturum, quod ne in ipsis quidem philosophis magnopere umquam probavi. quando enim Socrates, qui parens philosophiae iure dici potest, quicquam tale fecit? eorum erat iste mos qui tum sophistae nominabantur, quorum e numero primus est ausus Leontinus Gorgias in conventu poscere quaestionem, id est iubere dicere, qua de re quis vellet audire. audax negotium, dicerem impudens, nisi hoc institutum postea translatum ad philosophos nostros esset.

Sed et illum, quem nominavi, et ceteros sophistas, ut e Platone intellegi potest, lusos videmus a Socrate. is enim percontando atque interrogando elicere solebat eorum opiniones, quibuscum disserebat, ut ad ea, quae ii respondissent, si quid videretur, diceret. qui mos cum a posterioribus non esset retentus, Arcesilas eum revocavit instituitque ut ii, qui se audire vellent, non de se quaererent, sed ipsi dicerent, quid sentirent; quod cum dixissent, ille contra. sed eum qui audiebant, quoad poterant, defendebant sententiam suam. apud ceteros autem philosophos, qui quaesivit aliquid, tacet; quod quidem iam fit etiam in Academia. ubi enim is, qui audire vult, ita dixit: 'Voluptas mihi videtur esse summum bonum', perpetua oratione contra disputatur, ut facile intellegi possit eos, qui aliquid sibi videri dicant, non ipsos in ea sententia esse, sed audire velle contraria.
