In Fig.1, we show a partial Tropos goal model to clarify our goal analysis main
concepts. Actors (Customer IS and Mall Website) have a set of top-level goals (provide
information to customer), which are iteratively decomposed into subgoals by
and-decomposition (all subgoals should be achieved to fulfil the top goal) and ordecomposition (at least one subgoal should be achieved to fulfil the top goal). The goal
provide information to customer is and-decomposed into establish network connection,
get product identifier, and provide answer; the goal provide answer is or-decomposed
into query mall database and get answer through website. Goals are finally satisfied by
means of executable tasks; the goal “get product identifier” can be reached by one of
the tasks “read RFID tag”, “read barcode”, “let customer type product ID”.
A dependency indicates that an actor (depender) depends on another actor (dependee) to attain a goal or to execute a task: the actor Customer IS depends on the actor
Mall Website for achieving the goal get answer through website. Soft-goals are qualitative objectives for whose satisfaction there is no clear cut criteria (easy connection is
a rather vague objective), and they can be contributed either positively or negatively by
goals and tasks: establish wireless connection contributes positively to easy connection,
while establish wired connection contributes negatively to easy connection.