```scss
        .innerBlock {
          width: 93%;
          height: 100%;
          perspective: 1000px;
          position: relative;  overflow: hidden;
          transform-style: preserve-3d;
          transition: transform 0.6s;
        }

        &:hover .innerBlock {
          transform: rotateY(180deg);
        }
