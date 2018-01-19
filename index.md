---
layout: default
---

### Ον/μο Φοιτήτριας: Κολτσανίδου Ειρήνη

### ΑΜ: Π2013033

## Τίτλος: Super Mario

[**Link παιχνιδιού**](https://eiriniklt.github.io/Super-Mario/)

[**Link προσωπικού αποθετήριου**](https://github.com/eiriniklt/Super-Mario)

## ΕΙΣΑΓΩΓΗ

Το θέμα που αποφάσισα να επιλέξω για την υλοποίηση της εργαστηριακής εργασίας του μαθήματος Γ' εξαμήνου **Επικοινωνία Ανθρώπου - Υπολιστή** είναι το παιχνίδι **Super Mario Bros.**, το πρώτο παιχνίδι της σειράς Super Mario, το οποίο ήταν ένα απο τα αγαπημένα μου παιχνίδια απο όταν ήμουν μικρό παιδί. 

Το **Super Mario Bros.** είναι ένα βιντεοπαιχνίδι πλατφόρμας, που **δημιουργήθηκε από τη Nintendo** για το **Nintendo Entertainment System**. Κυκλοφόρησε στην Ιαπωνία στις 13 Σεπτεμβρίου του 1985, για το Family Computer, αργότερα την Αμερική για το Nintendo Entertainment System, την Ευρώπη στις 15 Μαΐου του 1987 και την Αυστραλία αργότερα το 1987.

Το **Super Mario Bros.** θεωρείται ως ένα από τα καλύτερα παιχνίδια που κυκλοφόρησαν ποτέ, καθώς έσωσε τη βιομηχανία των παιχνιδιών από μία τεράστια κρίση που άρχισε από το 1983 μέχρι το 1985. Το παιχνίδι βοήθησε στη διασημότητα του είδος side-scrolling. Ήταν, επίσης, το βιντεοπαιχνίδι με τις περισσότερες πωλήσεις για τρεις δεκαετίες, μέχρι που το ξεπέρασε το Wii Sports.

Ο σκοπός του παιχνιδιού είναι η ψυχαγωγία και η διασκέδαση.

## ΕΠΙΛΟΓΗ ΕΡΓΑΛΕΙΩΝ

### Για την υλοποίηση της εργασίας χρησιμοποιήθηκαν τα ακόλουθα εργαλεία:

- **WampServer** για την τοπική εκτέλεση του κώδικα (παιχνιδιού),
- **Notepad++** για την επεξεργασία/συγγραφή του κώδικα,
- **Tiled** για την δημιουργία της καινούριας πίστας και των layers,
- **Adobe Photoshop CC** για την επεξεργασία εικόνων και χαρακτήρων/εχθρών που χρησιμοποιήθηκαν

## ΔΙΑΔΙΚΑΣΙΑ ΑΝΑΠΤΥΞΗΣ

Ο παίκτης ελέγχει τον κύριο πρωταγωνιστή της σειράς, τον **Mario στον οποίο έγινε αλλαγή χρώματος στο ρούχο του σε πράσινο**. Μετακινείται από την αριστερή προς την δεξιά μεριά της οθόνης για να φτάσει στο τέλος της πίστας. **Έχουν προστεθεί διασπαρμένα κέρματα σε όλη την έκταση της πίστας** για να συλλέξει ο Mario όπου **ένα κέρμα αντιστοιχεί σε 10 πόντους** οι οποίοι **προστίθονται στο συνολικό σκορ**. Ο παίκτης έχει **διαθέσιμο ένα συγκεκριμένο νούμερο από ζωές και συγκεκριμένα τρεις**. Οι πιθανοί λόγοι για να χάσει μια ζωή είναι αν δεχτεί ζημιά από εχθρούς ή αν πέσει σε γκρεμό (στο κενό) . Ο Mario μπορεί να επιτεθεί σε εχθρούς, πηδώντας πάνω τους. Για παράδειγμα, ένας **Goomba** στον οποίο **έχει γίνει αλλαγή χρώματος σε μωβ** θα ισιώσει και θα ηττηθεί και όταν γίνει αυτό **ο παίκτης θα κερδίσει επιπλέον 20 πόντους** στο συνολικό του σκορ. **Το παιχνίδι τελειώνει όταν ο παίκτης ξεμείνει από ζωές και τότε εμφανίζεται στην οθόνη μύνημα ήττας (Game Over) με το συνολικό σκορ που έχει συγκεντρώσει απο την αρχή του παιχνιδιού**. Τέλος, έχουν προστεθεί διάφοροι ήχοι.

### Συνοπτικά οι αλλαγές που έχουν γίνει στο παιχνίδι είναι οι εξής:

- Αλλαγή χρώματος σε πράσινο στο ρούχο του Mario,
- Αλλαγή χρώματος σε μωβ στους εχθρούς Goombas,
- Διαθέσιμες τρείς ζωές,
- Διαθέσιμο σκορ, 10 πόντοι για κάθε κέρμα και 20 πόντοι για κάθε επίθεση σε κάποιο εχθρό,
- Μείωση μιας ζωής όταν πέφτει ο Mario στο γκρεμό (στο κενό) ή όταν σκοτωθεί (πέσει πάνω) απο κάποιο εχθρό,
- Προσθήκη ήχων για το background που παίζει σε όλη την διάρκεια του παιχνιδιού, όταν πηδάει, όταν μαζεύει κέρματα, όταν σκοτώνει έναν εχθρό και όταν χάνει το παιχνίδι,
- Τέλος παιχνιδιού όταν χαθούν και οι τρείς διαθέσιμες ζωές,
- Εμφάνιση μυνήματος ήττας (Game Over) με το συνολικό σκορ που έχει συγκεντρωθεί απο την αρχή του παιχνιδιού 

## ΕΝΔΕΙΚΤΙΚΕΣ ΟΘΟΝΕΣ

## ΣΥΜΠΕΡΑΣΜΑΤΑ

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
