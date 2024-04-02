```lilypond
\version "2.18.2"  % necessary for highlighting to work!

\header {
  title = "The Ruin King"
  composer = "ChatGPT"
}

\score {
  \relative c {
    \clef bass
    \key e \minor
    \time 4/4
    \tempo "Lento" 4 = 40

    % Measure 1
    e2._\markup { \italic dolce }  g4 |
    % Measure 2
    fis2 e4 d |
    % Measure 3
    e1~ |
    % Measure 4
    e2. b,4 |
    % Measure 5
    a'2 g4 fis |
    % Measure 6
    g1~ |
    % Measure 7
    g2 fis4 e |
    % Measure 8
    d1 |
    % Measure 9
    e2._\markup { \italic espressivo }  g4 |
    % Measure 10
    fis2 e4 d |
    % Measure 11
    e1~ |
    % Measure 12
    e2. b,4 |
    % Measure 13
    a'2 g4 fis |
    % Measure 14
    g1~ |
    % Measure 15
    g2 fis4 e |
    % Measure 16
    e1 \bar "|."
  }
  \layout { }
  \midi { }
}
