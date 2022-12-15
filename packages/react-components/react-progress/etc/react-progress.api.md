## API Report File for "@fluentui/react-progress"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { FieldControl } from '@fluentui/react-field';
import type { FieldProps } from '@fluentui/react-field';
import { FieldSlots } from '@fluentui/react-field';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import { SlotClassNames } from '@fluentui/react-utilities';

// @public @deprecated (undocumented)
export const Progress: React_2.ForwardRefExoticComponent<Omit<ComponentProps<ProgressBarSlots, "root">, "size"> & {
    shape?: "rounded" | "rectangular" | undefined;
    value?: number | undefined;
    max?: number | undefined;
    thickness?: "medium" | "large" | undefined;
    validationState?: "error" | "success" | "warning" | undefined;
} & React_2.RefAttributes<HTMLDivElement>>;

// @public
export const ProgressBar: ForwardRefComponent<ProgressBarProps>;

// @public (undocumented)
export const progressBarClassNames: SlotClassNames<ProgressBarSlots>;

// @public
export type ProgressBarProps = Omit<ComponentProps<ProgressBarSlots>, 'size'> & {
    shape?: 'rounded' | 'rectangular';
    value?: number;
    max?: number;
    thickness?: 'medium' | 'large';
    validationState?: 'success' | 'warning' | 'error';
};

// @public (undocumented)
export type ProgressBarSlots = {
    root: NonNullable<Slot<'div'>>;
    bar?: NonNullable<Slot<'div'>>;
};

// @public
export type ProgressBarState = ComponentState<ProgressBarSlots> & Required<Pick<ProgressBarProps, 'max' | 'shape' | 'thickness'>> & Pick<ProgressBarProps, 'value' | 'validationState'>;

// @public @deprecated (undocumented)
export const progressClassNames: SlotClassNames<ProgressBarSlots>;

// @public (undocumented)
export const ProgressField_unstable: ForwardRefComponent<ProgressFieldProps_unstable>;

// @public (undocumented)
export const progressFieldClassNames: SlotClassNames<FieldSlots<FieldControl>>;

// @public (undocumented)
export type ProgressFieldProps_unstable = FieldProps<typeof ProgressBar>;

// @public @deprecated (undocumented)
export type ProgressProps = ProgressBarProps;

// @public @deprecated (undocumented)
export type ProgressSlots = ProgressBarSlots;

// @public @deprecated (undocumented)
export type ProgressState = ProgressBarState;

// @public @deprecated (undocumented)
export const renderProgress_unstable: (state: ProgressBarState) => JSX.Element;

// @public
export const renderProgressBar_unstable: (state: ProgressBarState) => JSX.Element;

// @public @deprecated (undocumented)
export const useProgress_unstable: (props: ProgressBarProps, ref: React_2.Ref<HTMLElement>) => ProgressBarState;

// @public
export const useProgressBar_unstable: (props: ProgressBarProps, ref: React_2.Ref<HTMLElement>) => ProgressBarState;

// @public
export const useProgressBarStyles_unstable: (state: ProgressBarState) => ProgressBarState;

// @public @deprecated (undocumented)
export const useProgressStyles_unstable: (state: ProgressBarState) => ProgressBarState;

// (No @packageDocumentation comment for this package)

```